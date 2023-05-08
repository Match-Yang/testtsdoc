


# getCallkitPerformSetGroupCallActionEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformSetGroupCallActionEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformSetGroupCallActionEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitPerformSetGroupCallActionEvent
      .stream;
}
```







