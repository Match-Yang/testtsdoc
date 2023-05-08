


# setANSMode method








Future&lt;void> setANSMode
([ZegoANSMode](../../zego_uikit_prebuilt_live_audio_room/ZegoANSMode.md) mode)





<p>Sets the automatic noise suppression (ANS) mode.</p>
<p>Available since: 1.1.0
Description: When <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableANS.md">enableANS</a> is used to enable noise suppression, this function can be used to switch between different noise suppression modes to control the degree of noise suppression.
Use case: When the default noise suppression effect does not meet expectations, this function can be used to adjust the noise suppression mode.
Default value: When this function is not called, the default echo cancellation mode is <code>Medium</code>.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code>.
Restrictions: The value set by this function is valid only after the noise suppression function is turned on.</p>
<ul>
<li><code>mode</code> Audio Noise Suppression mode</li>
</ul>



## Implementation

```dart
Future<void> setANSMode(ZegoANSMode mode) async {
  return await ZegoExpressImpl.instance.setANSMode(mode);
}
```







