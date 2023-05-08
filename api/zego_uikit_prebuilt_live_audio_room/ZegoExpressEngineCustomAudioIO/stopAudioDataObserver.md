


# stopAudioDataObserver method








Future&lt;void> stopAudioDataObserver
()





<p>Disable audio data observering.</p>
<p>Available since: 1.1.0
Description: Disable audio data observering.
Use cases: When develop need to monitor the original audio.
When to call: After calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/startAudioDataObserver.md">startAudioDataObserver</a> to start audio data monitoring.</p>



## Implementation

```dart
Future<void> stopAudioDataObserver() async {
  return await ZegoExpressImpl.instance.stopAudioDataObserver();
}
```







