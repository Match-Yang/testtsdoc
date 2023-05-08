


# getCallkitPerformSetHeldCallActionEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformSetHeldCallActionEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformSetHeldCallActionEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitPerformSetHeldCallActionEvent
      .stream;
}
```







