


# getCallkitPerformEndCallActionEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformEndCallActionEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformEndCallActionEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitPerformEndCallActionEvent
      .stream;
}
```







