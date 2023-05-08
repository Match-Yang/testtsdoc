


# getCallkitDeactivateAudioEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)> getCallkitDeactivateAudioEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitVoidEvent>
    getCallkitDeactivateAudioEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitDeactivateAudioEvent
      .stream;
}
```







