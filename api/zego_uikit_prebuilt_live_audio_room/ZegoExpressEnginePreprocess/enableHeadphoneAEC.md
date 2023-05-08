


# enableHeadphoneAEC method








Future&lt;void> enableHeadphoneAEC
(bool enable)





<p>Whether to turn on acoustic echo cancellation (AEC) when using the headphone.</p>
<p>Available since: 1.1.0
Description: When <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableAEC.md">enableAEC</a> is used to turn on echo cancellation, it is only turned on when the speaker is used for mobile terminal equipment. Call this function if you need to turn echo cancellation on or off when using the headset.
Use case: It is common when the mobile device is connected to a external sound card as the audio output source. In order to eliminate the echo in this case, you need to call this function to turn on the echo cancellation.
Default value: Android is off by default and iOS is on by default.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code>.
Caution: Turning on echo cancellation will increase the ear return delay. On the iOS platform, the SDK cannot distinguish between the headset and the external sound card. If you use this function to turn off the system echo cancellation when using the headset, the sound played by the external sound card will be collected when the user accesses the external sound card.
Restrictions: None.
Related APIs: When the headset is not used, you can set whether the SDK turns on echo cancellation through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableAEC.md">enableAEC</a>.
Platform differences: Only supports iOS and Android.</p>
<ul>
<li><code>enable</code> Whether to enable, true: enable, false: disable</li>
</ul>



## Implementation

```dart
Future<void> enableHeadphoneAEC(bool enable) async {
  return await ZegoExpressImpl.instance.enableHeadphoneAEC(enable);
}
```







