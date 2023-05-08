


# getCallkitActivateAudioEventStream method








Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)> getCallkitActivateAudioEventStream
()

_<span class="feature">inherited</span>_



<p>Called when the provider's audio session activation state changes.</p>



## Implementation

```dart
Stream<ZegoSignalingPluginCallKitVoidEvent>
    getCallkitActivateAudioEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitActivateAudioEventStream();
}
```







