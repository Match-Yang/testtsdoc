


# enableCustomAudioPlaybackProcessing method








Future&lt;void> enableCustomAudioPlaybackProcessing
(bool enable, [ZegoCustomAudioProcessConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig-class.md) config)





<p>Enable custom audio processing for SDK playback audio data.</p>
<p>Available since: 1.13.0
Description: Enable remote streaming custom audio processing, developers can receive remote streaming audio frames through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onProcessRemoteAudioData.md">onProcessRemoteAudioData</a>, and can modify the audio data.
Use cases: If the developer wants to implement special functions (such as voice change, bel canto, etc.) through custom processing after collecting audio data.
When to call: It needs to be called before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code> to be effective.
Restrictions: None.</p>
<ul>
<li><code>enable</code> Whether to enable custom audio processing for SDK playback audio data.</li>
<li><code>config</code> Custom audio processing configuration.</li>
</ul>



## Implementation

```dart
Future<void> enableCustomAudioPlaybackProcessing(
    bool enable, ZegoCustomAudioProcessConfig config) async {
  return await ZegoExpressImpl.instance
      .enableCustomAudioPlaybackProcessing(enable, config);
}
```







