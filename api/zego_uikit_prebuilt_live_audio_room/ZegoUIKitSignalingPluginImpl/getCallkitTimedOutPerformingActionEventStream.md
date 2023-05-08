


# getCallkitTimedOutPerformingActionEventStream method








Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitTimedOutPerformingActionEventStream
()

_<span class="feature">inherited</span>_



<p>Called when an action was not performed in time and has been inherently failed. Depending on the action, this timeout may also force the call to end. An action that has already timed out should not be fulfilled or failed by the provider delegate</p>



## Implementation

```dart
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitTimedOutPerformingActionEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitTimedOutPerformingActionEventStream();
}
```







