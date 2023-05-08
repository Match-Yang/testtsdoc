


# enableCustomAudioIO method








Future&lt;void> enableCustomAudioIO
(bool enable, [ZegoCustomAudioConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioConfig-class.md) config, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Enables the custom audio I/O function (for the specified channel), support PCM, AAC format data.</p>
<p>Available since: 1.10.0
Description: Enable custom audio IO function, support PCM, AAC format data.
Use cases: If the developer wants to implement special functions (such as voice change, bel canto, etc.) through custom processing after the audio data is collected or before the remote audio data is drawn for rendering.
When to call: It needs to be called before <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>startPreview</code>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code> to be effective.
Restrictions: None.</p>
<ul>
<li><code>enable</code> Whether to enable custom audio IO, default is false.</li>
<li><code>config</code> Custom audio IO config.</li>
<li><code>channel</code> Specify the publish channel to enable custom audio IO.</li>
</ul>



## Implementation

```dart
Future<void> enableCustomAudioIO(bool enable, ZegoCustomAudioConfig config,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .enableCustomAudioIO(enable, config, channel: channel);
}
```







