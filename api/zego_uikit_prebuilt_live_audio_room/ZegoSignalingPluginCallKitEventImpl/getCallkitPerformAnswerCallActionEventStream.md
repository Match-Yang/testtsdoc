


# getCallkitPerformAnswerCallActionEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformAnswerCallActionEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformAnswerCallActionEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitPerformAnswerCallActionEvent
      .stream;
}
```







