


# enableCustomAudioCaptureProcessingAfterHeadphoneMonitor method








Future&lt;void> enableCustomAudioCaptureProcessingAfterHeadphoneMonitor
(bool enable, [ZegoCustomAudioProcessConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig-class.md) config)





<p>Turn on local collection and custom audio processing (after ear return).</p>
<p>Available since: 1.13.0
Description: Enable custom audio processing(after ear return), developers can receive locally collected audio frames through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onProcessCapturedAudioData.md">onProcessCapturedAudioData</a>, and can modify the audio data.
Use cases: If the developer wants to implement special functions (such as voice change, bel canto, etc.) through custom processing after the audio data is collected or before the remote audio data is drawn for rendering.
When to call: It needs to be called before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code> to be effective.
Restrictions: None.</p>
<ul>
<li><code>enable</code> Whether to enable local capture custom audio processing.</li>
<li><code>config</code> Custom audio processing configuration.</li>
</ul>



## Implementation

```dart
Future<void> enableCustomAudioCaptureProcessingAfterHeadphoneMonitor(
    bool enable, ZegoCustomAudioProcessConfig config) async {
  return await ZegoExpressImpl.instance
      .enableCustomAudioCaptureProcessingAfterHeadphoneMonitor(
          enable, config);
}
```







