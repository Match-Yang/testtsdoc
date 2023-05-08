


# getCallkitPerformSetHeldCallActionEventStream method








Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformSetHeldCallActionEventStream
()

_<span class="feature">inherited</span>_






## Implementation

```dart
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformSetHeldCallActionEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitPerformSetHeldCallActionEventStream();
}
```







