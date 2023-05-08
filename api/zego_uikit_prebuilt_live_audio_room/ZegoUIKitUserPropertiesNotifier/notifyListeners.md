


# notifyListeners method







- @protected
- @visibleForTesting

void notifyListeners
()

_<span class="feature">inherited</span>_



<p>Call all the registered listeners.</p>
<p>Call this method whenever the object changes, to notify any clients the
object may have changed. Listeners that are added during this iteration
will not be visited. Listeners that are removed during this iteration will
not be visited after they are removed.</p>
<p>Exceptions thrown by listeners will be caught and reported using
<code>FlutterError.reportError</code>.</p>
<p>This method must not be called after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/dispose.md">dispose</a> has been called.</p>
<p>Surprising behavior can result when reentrantly removing a listener (e.g.
in response to a notification) that has been registered multiple times.
See the discussion at <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/removeListener.md">removeListener</a>.</p>



## Implementation

```dart
@protected
@visibleForTesting
@pragma('vm:notify-debugger-on-exception')
void notifyListeners() {
  assert(ChangeNotifier.debugAssertNotDisposed(this));
  if (_count == 0) {
    return;
  }

  // To make sure that listeners removed during this iteration are not called,
  // we set them to null, but we don't shrink the list right away.
  // By doing this, we can continue to iterate on our list until it reaches
  // the last listener added before the call to this method.

  // To allow potential listeners to recursively call notifyListener, we track
  // the number of times this method is called in _notificationCallStackDepth.
  // Once every recursive iteration is finished (i.e. when _notificationCallStackDepth == 0),
  // we can safely shrink our list so that it will only contain not null
  // listeners.

  _notificationCallStackDepth++;

  final int end = _count;
  for (int i = 0; i < end; i++) {
    try {
      _listeners[i]?.call();
    } catch (exception, stack) {
      FlutterError.reportError(FlutterErrorDetails(
        exception: exception,
        stack: stack,
        library: 'foundation library',
        context: ErrorDescription('while dispatching notifications for $runtimeType'),
        informationCollector: () => <DiagnosticsNode>[
          DiagnosticsProperty<ChangeNotifier>(
            'The $runtimeType sending notification was',
            this,
            style: DiagnosticsTreeStyle.errorProperty,
          ),
        ],
      ));
    }
  }

  _notificationCallStackDepth--;

  if (_notificationCallStackDepth == 0 && _reentrantlyRemovedListeners > 0) {
    // We really remove the listeners when all notifications are done.
    final int newLength = _count - _reentrantlyRemovedListeners;
    if (newLength * 2 <= _listeners.length) {
      // As in _removeAt, we only shrink the list when the real number of
      // listeners is half the length of our list.
      final List<VoidCallback?> newListeners = List<VoidCallback?>.filled(newLength, null);

      int newIndex = 0;
      for (int i = 0; i < _count; i++) {
        final VoidCallback? listener = _listeners[i];
        if (listener != null) {
          newListeners[newIndex++] = listener;
        }
      }

      _listeners = newListeners;
    } else {
      // Otherwise we put all the null references at the end.
      for (int i = 0; i < newLength; i += 1) {
        if (_listeners[i] == null) {
          // We swap this item with the next not null item.
          int swapIndex = i + 1;
          while(_listeners[swapIndex] == null) {
            swapIndex += 1;
          }
          _listeners[i] = _listeners[swapIndex];
          _listeners[swapIndex] = null;
        }
      }
    }

    _reentrantlyRemovedListeners = 0;
    _count = newLength;
  }
}
```







