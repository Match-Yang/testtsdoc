


# getCallkitPerformPlayDTMFCallActionEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformPlayDTMFCallActionEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformPlayDTMFCallActionEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitPerformPlayDTMFCallActionEvent
      .stream;
}
```







