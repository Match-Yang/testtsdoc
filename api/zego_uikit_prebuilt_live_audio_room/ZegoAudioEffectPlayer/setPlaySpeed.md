


# setPlaySpeed method








Future&lt;void> setPlaySpeed
(int audioEffectID, double speed)





<p>Set the playback speed for a given audio effect. Both the local play speed and the publish speed are set. (separate settings are not supported).</p>
<p>Available since: 2.18.0
Description: Set the playback speed for a given audio effect. Both the local play speed and the publish speed are set. (separate settings are not supported).
When to call: The specified <code>audioEffectID</code> is <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/start.md">start</a>.
Restrictions: None.</p>
<ul>
<li><code>audioEffectID</code> ID for the audio effect.</li>
<li><code>speed</code> The speed of play. <br>Value range: The range is 0.5 ~ 2.0. <br>Default value: The default is 1.0.</li>
</ul>



## Implementation

```dart
Future<void> setPlaySpeed(int audioEffectID, double speed);
```







