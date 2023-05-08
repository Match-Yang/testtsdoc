


# enableAEC method








Future&lt;void> enableAEC
(bool enable)





<p>Whether to enable acoustic echo cancellation (AEC).</p>
<p>Available since: 1.1.0
Description: Turning on echo cancellation, the SDK filters the collected audio data to reduce the echo component in the audio.
Use case: When you need to reduce the echo to improve the call quality and user experience, you can turn on this feature.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code>.
Caution: The AEC function only supports the processing of sounds playbacked through the SDK, such as sounds played by the playing stream, media player, audio effect player, etc. Before this function is called, the SDK automatically determines whether to use AEC. Once this function is called, the SDK does not automatically determine whether to use AEC.
Restrictions: None.
Related APIs: Developers can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableHeadphoneAEC.md">enableHeadphoneAEC</a> to set whether to enable AEC when using headphones, and use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setAECMode.md">setAECMode</a> to set the echo cancellation mode.</p>
<ul>
<li><code>enable</code> Whether to enable echo cancellation, true: enable, false: disable</li>
</ul>



## Implementation

```dart
Future<void> enableAEC(bool enable) async {
  return await ZegoExpressImpl.instance.enableAEC(enable);
}
```







