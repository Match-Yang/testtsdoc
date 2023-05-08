


# setAECMode method








Future&lt;void> setAECMode
([ZegoAECMode](../../zego_uikit_prebuilt_live_audio_room/ZegoAECMode.md) mode)





<p>Sets the acoustic echo cancellation (AEC) mode.</p>
<p>Available since: 1.1.0
Description: When <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableAEC.md">enableAEC</a> is used to enable echo cancellation, this function can be used to switch between different echo cancellation modes to control the degree of echo cancellation.
Use case: When the default echo cancellation effect does not meet expectations, this function can be used to adjust the echo cancellation mode.
Default value: When this function is not called, the default echo cancellation mode is <code>Aggressive</code>.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code>.
Restrictions: The value set by this function is valid only after the echo cancellation function is turned on.</p>
<ul>
<li><code>mode</code> Echo cancellation mode</li>
</ul>



## Implementation

```dart
Future<void> setAECMode(ZegoAECMode mode) async {
  return await ZegoExpressImpl.instance.setAECMode(mode);
}
```







