


# getCallkitPerformPlayDTMFCallActionEventStream method








Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)> getCallkitPerformPlayDTMFCallActionEventStream
()

_<span class="feature">inherited</span>_






## Implementation

```dart
Stream<ZegoSignalingPluginCallKitActionEvent>
    getCallkitPerformPlayDTMFCallActionEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitPerformPlayDTMFCallActionEventStream();
}
```







