


# createAudioEffectPlayer method








Future&lt;[ZegoAudioEffectPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer-class.md)?> createAudioEffectPlayer
()





<p>Creates a audio effect player instance.</p>
<p>Available since: 1.16.0
Description: Creates a audio effect player instance.
Use cases: When you need to play short sound effects, such as applause, cheers, etc., you can use audioEffectPlayer to achieve.
When to call: It can be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Currently, a maximum of 1 instances can be created, after which it will return null.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineAudioEffectPlayer/destroyAudioEffectPlayer.md">destroyAudioEffectPlayer</a>.</p>
<ul>
<li>Returns audio effect player instance, null will be returned when the maximum number is exceeded.</li>
</ul>



## Implementation

```dart
Future<ZegoAudioEffectPlayer?> createAudioEffectPlayer() async {
  return await ZegoExpressImpl.instance.createAudioEffectPlayer();
}
```







