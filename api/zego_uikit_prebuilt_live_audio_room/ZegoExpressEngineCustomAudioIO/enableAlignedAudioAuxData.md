


# enableAlignedAudioAuxData method








Future&lt;void> enableAlignedAudioAuxData
(bool enable, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)





<p>Enable feature of throwing audio aux frames which aligned with accompany.</p>
<p>Available since: 2.22.0
Description: Enable feature of throwing audio aux frames which aligned with accompany, and developers can receive the aligned audio aux frame through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAlignedAudioAuxData.md">onAlignedAudioAuxData</a>.
Use cases: In KTV scene, this function can be used if the user wants to record voice and accompaniment for free processing.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> to be effective.
Restrictions: None.
Caution: When throwing onAlignedAudioAuxData audio aux frames is enabled, the streaming data of <code>startPublishingStream</code> does not contain audio aux frames.</p>
<ul>
<li><code>enable</code> Whether to enable the feature of throwing alignmented audio aux frames.</li>
<li><code>param</code> param of audio frame. Currently supports 8k, 16k, 32k, 44.1k, 48k sampling rate, mono or stereo.</li>
</ul>



## Implementation

```dart
Future<void> enableAlignedAudioAuxData(
    bool enable, ZegoAudioFrameParam param) async {
  return await ZegoExpressImpl.instance
      .enableAlignedAudioAuxData(enable, param);
}
```







