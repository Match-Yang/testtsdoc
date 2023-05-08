


# stopAudioSpectrumMonitor method








Future&lt;void> stopAudioSpectrumMonitor
()





<p>Stops audio spectrum monitoring.</p>
<p>Available since: 1.1.0
Description: After the monitoring is stopped, the callback of the local/remote audio spectrum will be stopped.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Related APIs: Audio spectrum monitoring can be initiated via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/startAudioSpectrumMonitor.md">startAudioSpectrumMonitor</a>.</p>



## Implementation

```dart
Future<void> stopAudioSpectrumMonitor() async {
  return await ZegoExpressImpl.instance.stopAudioSpectrumMonitor();
}
```







