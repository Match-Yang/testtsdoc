


# startAudioSpectrumMonitor method








Future&lt;void> startAudioSpectrumMonitor
({int? millisecond})





<p>Starts audio spectrum monitoring. Support setting the listening interval.</p>
<p>Available since: 1.15.0
Description: After starting monitoring, you can receive local audio spectrum via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedAudioSpectrumUpdate.md">onCapturedAudioSpectrumUpdate</a> callback, and receive remote audio spectrum via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteAudioSpectrumUpdate.md">onRemoteAudioSpectrumUpdate</a> callback.
Use cases: In the host K song scene, has been published or played under the premise that the host or audience to see the tone and volume change animation.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedAudioSpectrumUpdate.md">onCapturedAudioSpectrumUpdate</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteAudioSpectrumUpdate.md">onRemoteAudioSpectrumUpdate</a> callback notification period is the value set by the parameter.</p>
<ul>
<li><code>millisecond</code> Monitoring time period of the audio spectrum, in milliseconds, has a value range of <code>100, 3000</code>. Default is 100 ms.</li>
</ul>



## Implementation

```dart
Future<void> startAudioSpectrumMonitor({int? millisecond}) async {
  return await ZegoExpressImpl.instance
      .startAudioSpectrumMonitor(millisecond: millisecond);
}
```







