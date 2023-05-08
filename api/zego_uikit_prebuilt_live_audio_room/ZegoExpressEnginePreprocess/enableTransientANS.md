


# enableTransientANS method








Future&lt;void> enableTransientANS
(bool enable)





<p>Enables or disables transient noise suppression.</p>
<p>Available since: 1.17.0
Description: Enable the transient noise suppression can suppress the noises such as keyboard and desk knocks.
Use case: When you need to suppress transient noise to improve call quality and user experience, you can turn on this feature.
Default value: When this function is not called, this is disabled by default.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code>.
Related APIs: This function will not suppress normal noise after it is turned on. If you need to turn on normal noise suppression, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableANS.md">enableANS</a>.
Restrictions: None.</p>
<ul>
<li><code>enable</code> Whether to enable transient noise suppression, true: enable, false: disable</li>
</ul>



## Implementation

```dart
Future<void> enableTransientANS(bool enable) async {
  return await ZegoExpressImpl.instance.enableTransientANS(enable);
}
```







