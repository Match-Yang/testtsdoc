


# getCallkitPerformSetGroupCallActionEventStream method








Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformSetGroupCallActionEventStream
()

_<span class="feature">inherited</span>_






## Implementation

```dart
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformSetGroupCallActionEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitPerformSetGroupCallActionEventStream();
}
```







