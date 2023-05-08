


# enableANS method








Future&lt;void> enableANS
(bool enable)





<p>Enables or disables active noise suppression (ANS, aka ANC).</p>
<p>Available since: 1.1.0
Description: Enable the noise suppression can reduce the noise in the audio data and make the human voice clearer.
Use case: When you need to suppress noise to improve call quality and user experience, you can turn on this feature.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code>.
Related APIs: This function has a better suppression effect on continuous noise (such as the sound of rain, white noise). If you need to turn on transient noise suppression, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableTransientANS.md">enableTransientANS</a>. And the noise suppression mode can be set by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setANSMode.md">setANSMode</a>.
Caution: Before this function is called, the SDK automatically determines whether to use ANS. Once this function is called, the SDK does not automatically determine whether to use ANS.
Restrictions: None.</p>
<ul>
<li><code>enable</code> Whether to enable noise suppression, true: enable, false: disable</li>
</ul>



## Implementation

```dart
Future<void> enableANS(bool enable) async {
  return await ZegoExpressImpl.instance.enableANS(enable);
}
```







