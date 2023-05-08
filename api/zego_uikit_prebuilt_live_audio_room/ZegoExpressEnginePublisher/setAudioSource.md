


# setAudioSource method








Future&lt;int> setAudioSource
([ZegoAudioSourceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) source, {[ZegoAudioSourceMixConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceMixConfig-class.md)? config, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set audio capture source with audio mix config.</p>
<p>Available since: 3.1.0
Description: Set audio capture source for switching between different audio capture sources.
Use cases: Typically used in educational scenarios that require switching between different audio capture sources.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Calling in publishing or preview is invalid when using the web platform.
Caution: 1. Main push channel ZegoPublishChannel.Main does not support using ZegoAudioSourceType.MediaPlayer and ZegoAudioSourceType.MainPublishChannel audio source type.
 2. When using ZegoAudioSourceType.MediaPlayer and ZegoAudioSourceType.MainPublishChannel audio source type in aux publish channel ZegoPublishChannel.Aux, must ensure that physical device works on main publish channel ZegoPublishChannel.Main.
 3. config applies only to the main channel ZegoPublishChannel.Main, This parameter is invalid when the channel is not the main channel.</p>
<ul>
<li><code>source</code> Audio capture source.</li>
<li><code>config</code> Audio capture source mix config. This parameter applies only to the Main push channel ZegoPublishChannel. main. This parameter is invalid when channel is not the main push channel.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<int> setAudioSource(ZegoAudioSourceType source,
    {ZegoAudioSourceMixConfig? config, ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setAudioSource(source, config: config, channel: channel);
}
```







