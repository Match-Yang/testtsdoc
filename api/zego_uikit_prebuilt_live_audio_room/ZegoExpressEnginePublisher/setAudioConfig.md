


# setAudioConfig method








Future&lt;void> setAudioConfig
([ZegoAudioConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioConfig-class.md) config, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets up the audio configurations for the specified publish channel.</p>
<p>Available since: 1.3.4
Description: You can set the combined value of the audio codec, bit rate, and audio channel through this function. If the preset value cannot meet the developer's scenario, the developer can set the parameters according to the business requirements.
Default value: The default audio config refers to the default value of <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioConfig-class.md">ZegoAudioConfig</a>.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, and before publishing <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/getAudioConfig.md">getAudioConfig</a>.</p>
<ul>
<li><code>config</code> Audio config.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setAudioConfig(ZegoAudioConfig config,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setAudioConfig(config, channel: channel);
}
```







