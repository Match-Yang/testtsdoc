


# addListener method







- @override

void addListener
(VoidCallback listener)

_<span class="feature">inherited</span>_



<p>Register a closure to be called when the object changes.</p>
<p>If the given closure is already registered, an additional instance is
added, and must be removed the same number of times it is added before it
will stop being called.</p>
<p>This method must not be called after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/dispose.md">dispose</a> has been called.</p>
<p>If a listener is added twice, and is removed once during an iteration
(e.g. in response to a notification), it will still be called again. If,
on the other hand, it is removed as many times as it was registered, then
it will no longer be called. This odd behavior is the result of the
<code>ChangeNotifier</code> not being able to determine which listener is being
removed, since they are identical, therefore it will conservatively still
call all the listeners when it knows that any are still registered.</p>
<p>This surprising behavior can be unexpectedly observed when registering a
listener on two separate objects which are both forwarding all
registrations to a common upstream object.</p>
<p>See also:</p>
<ul>
<li><a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/removeListener.md">removeListener</a>, which removes a previously registered closure from
the list of closures that are notified when the object changes.</li>
</ul>



## Implementation

```dart
@override
void addListener(VoidCallback listener) {
  assert(ChangeNotifier.debugAssertNotDisposed(this));
  if (kFlutterMemoryAllocationsEnabled && !_creationDispatched) {
    MemoryAllocations.instance.dispatchObjectCreated(
      library: _flutterFoundationLibrary,
      className: '$ChangeNotifier',
      object: this,
    );
    _creationDispatched = true;
  }
  if (_count == _listeners.length) {
    if (_count == 0) {
      _listeners = List<VoidCallback?>.filled(1, null);
    } else {
      final List<VoidCallback?> newListeners =
          List<VoidCallback?>.filled(_listeners.length * 2, null);
      for (int i = 0; i < _count; i++) {
        newListeners[i] = _listeners[i];
      }
      _listeners = newListeners;
    }
  }
  _listeners[_count++] = listener;
}
```







