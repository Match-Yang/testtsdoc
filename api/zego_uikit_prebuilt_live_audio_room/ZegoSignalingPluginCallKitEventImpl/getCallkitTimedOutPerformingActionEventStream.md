


# getCallkitTimedOutPerformingActionEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitTimedOutPerformingActionEventStream
()

_<span class="feature">override</span>_



<p>Called when an action was not performed in time and has been inherently failed. Depending on the action, this timeout may also force the call to end. An action that has already timed out should not be fulfilled or failed by the provider delegate</p>



## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitTimedOutPerformingActionEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitTimedOutPerformingActionEvent
      .stream;
}
```







