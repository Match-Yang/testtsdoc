


# enableAGC method








Future&lt;void> enableAGC
(bool enable)





<p>Enables or disables automatic gain control (AGC).</p>
<p>Available since: 1.1.0
Description: After turning on this function, the SDK can automatically adjust the microphone volume to adapt to near and far sound pickups and keep the volume stable.
Use case: When you need to ensure volume stability to improve call quality and user experience, you can turn on this feature.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> and before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code>. Note that the Mac needs to be called after <code>startPreview</code> and before <code>startPublishingStream</code>.
Caution: Before this function is called, the SDK automatically determines whether to use AGC. Once this function is called, the SDK does not automatically determine whether to use AGC.
Restrictions: None.</p>
<ul>
<li><code>enable</code> Whether to enable automatic gain control, true: enable, false: disable</li>
</ul>



## Implementation

```dart
Future<void> enableAGC(bool enable) async {
  return await ZegoExpressImpl.instance.enableAGC(enable);
}
```







