


# destroyAudioEffectPlayer method








Future&lt;void> destroyAudioEffectPlayer
([ZegoAudioEffectPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer-class.md) audioEffectPlayer)





<p>Destroys a audio effect player instance.</p>
<p>Available since: 1.16.0
Description: Destroys the specified audio effect player instance.
When to call: It can be called after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineAudioEffectPlayer/createAudioEffectPlayer.md">createAudioEffectPlayer</a>.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineAudioEffectPlayer/createAudioEffectPlayer.md">createAudioEffectPlayer</a>.</p>
<ul>
<li><code>audioEffectPlayer</code> The audio effect player instance object to be destroyed.</li>
</ul>



## Implementation

```dart
Future<void> destroyAudioEffectPlayer(
    ZegoAudioEffectPlayer audioEffectPlayer) async {
  return await ZegoExpressImpl.instance
      .destroyAudioEffectPlayer(audioEffectPlayer);
}
```







