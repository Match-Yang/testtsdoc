


# getCallkitActivateAudioEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)> getCallkitActivateAudioEventStream
()

_<span class="feature">override</span>_



<p>Called when the provider's audio session activation state changes.</p>



## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitVoidEvent>
    getCallkitActivateAudioEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitActivateAudioEvent
      .stream;
}
```







