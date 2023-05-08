


# dispose method







- @mustCallSuper

void dispose
()

_<span class="feature">inherited</span>_



<p>Discards any resources used by the object. After this is called, the
object is not in a usable state and should be discarded (calls to
<a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/addListener.md">addListener</a> will throw after the object is disposed).</p>
<p>This method should only be called by the object's owner.</p>
<p>This method does not notify listeners, and clears the listener list once
it is called. Consumers of this class must decide on whether to notify
listeners or not immediately before disposal.</p>



## Implementation

```dart
@mustCallSuper
void dispose() {
  assert(ChangeNotifier.debugAssertNotDisposed(this));
  assert(
    _notificationCallStackDepth == 0,
    'The "dispose()" method on $this was called during the call to '
    '"notifyListeners()". This is likely to cause errors since it modifies '
    'the list of listeners while the list is being used.',
  );
  assert(() {
    _debugDisposed = true;
    return true;
  }());
  if (kFlutterMemoryAllocationsEnabled && _creationDispatched) {
    MemoryAllocations.instance.dispatchObjectDisposed(object: this);
  }
  _listeners = _emptyListeners;
  _count = 0;
}
```







