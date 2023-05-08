


# getCallkitDeactivateAudioEventStream method








Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)> getCallkitDeactivateAudioEventStream
()

_<span class="feature">inherited</span>_






## Implementation

```dart
Stream<ZegoSignalingPluginCallKitVoidEvent>
    getCallkitDeactivateAudioEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitDeactivateAudioEventStream();
}
```







