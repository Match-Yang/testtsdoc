


# removeListener method







- @override

void removeListener
(VoidCallback listener)

_<span class="feature">inherited</span>_



<p>Remove a previously registered closure from the list of closures that are
notified when the object changes.</p>
<p>If the given listener is not registered, the call is ignored.</p>
<p>This method returns immediately if <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/dispose.md">dispose</a> has been called.</p>
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
<li><a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/addListener.md">addListener</a>, which registers a closure to be called when the object
changes.</li>
</ul>



## Implementation

```dart
@override
void removeListener(VoidCallback listener) {
  // This method is allowed to be called on disposed instances for usability
  // reasons. Due to how our frame scheduling logic between render objects and
  // overlays, it is common that the owner of this instance would be disposed a
  // frame earlier than the listeners. Allowing calls to this method after it
  // is disposed makes it easier for listeners to properly clean up.
  for (int i = 0; i < _count; i++) {
    final VoidCallback? listenerAtIndex = _listeners[i];
    if (listenerAtIndex == listener) {
      if (_notificationCallStackDepth > 0) {
        // We don't resize the list during notifyListeners iterations
        // but we set to null, the listeners we want to remove. We will
        // effectively resize the list at the end of all notifyListeners
        // iterations.
        _listeners[i] = null;
        _reentrantlyRemovedListeners++;
      } else {
        // When we are outside the notifyListeners iterations we can
        // effectively shrink the list.
        _removeAt(i);
      }
      break;
    }
  }
}
```







