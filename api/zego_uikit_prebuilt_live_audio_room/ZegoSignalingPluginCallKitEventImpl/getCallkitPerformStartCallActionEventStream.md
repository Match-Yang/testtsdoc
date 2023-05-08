


# getCallkitPerformStartCallActionEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformStartCallActionEventStream
()

_<span class="feature">override</span>_



<p>each perform*CallAction method is called sequentially for each action in the transaction</p>



## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformStartCallActionEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitPerformStartCallActionEvent
      .stream;
}
```







