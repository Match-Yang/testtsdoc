


# hasListeners property









**Annotations**

- @protected
bool hasListeners
  
_<span class="feature">inherited</span>_



<p>Whether any listeners are currently registered.</p>
<p>Clients should not depend on this value for their behavior, because having
one listener's logic change when another listener happens to start or stop
listening will lead to extremely hard-to-track bugs. Subclasses might use
this information to determine whether to do any work when there are no
listeners, however; for example, resuming a <code>Stream</code> when a listener is
added and pausing it when a listener is removed.</p>
<p>Typically this is used by overriding <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/addListener.md">addListener</a>, checking if
<a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/hasListeners.md">hasListeners</a> is false before calling <code>super.addListener()</code>, and if so,
starting whatever work is needed to determine when to call
<a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/notifyListeners.md">notifyListeners</a>; and similarly, by overriding <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/removeListener.md">removeListener</a>, checking
if <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/hasListeners.md">hasListeners</a> is false after calling <code>super.removeListener()</code>, and if
so, stopping that same work.</p>
<p>This method returns false if <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUserPropertiesNotifier/dispose.md">dispose</a> has been called.</p>



## Implementation

```dart
@protected
bool get hasListeners => _count > 0;
```








