


# start method








Future&lt;void> start
(int audioEffectID, {String? path, [ZegoAudioEffectPlayConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayConfig-class.md)? config})





<p>Start playing audio effect.</p>
<p>Available since: 1.16.0
Description: Start playing audio effect. The default is only played once and is not mixed into the publishing stream, if you want to change this please modify <code>config</code> param.
Use cases: When you need to play short sound effects, such as applause, cheers, etc., you can use this interface to achieve, and further configure the number of plays through the <code>config</code> parameter, and mix the sound effects into the push stream.
When to call: It can be called after <code>createAudioEffectPlayer</code>.
Restrictions: None.</p>
<ul>
<li><code>audioEffectID</code> Description: ID for the audio effect. The SDK uses audioEffectID to control the playback of sound effects. The SDK does not force the user to pass in this parameter as a fixed value. It is best to ensure that each sound effect can have a unique ID. The recommended methods are static self-incrementing ID or the hash of the incoming sound effect file path.</li>
<li><code>path</code> The absolute path of the local resource or "assets://" . <br>Value range: "ipod-library://" and network url are not supported. Set path as null or "" if resource is loaded already using <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/loadResource.md">loadResource</a>.</li>
<li><code>config</code> Audio effect playback configuration. <br>Default value: Set null will only be played once, and will not be mixed into the publishing stream.</li>
</ul>



## Implementation

```dart
Future<void> start(int audioEffectID,
    {String? path, ZegoAudioEffectPlayConfig? config});
```







