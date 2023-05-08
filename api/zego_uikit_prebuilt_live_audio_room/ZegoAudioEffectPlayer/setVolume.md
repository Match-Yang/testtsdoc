


# setVolume method








Future&lt;void> setVolume
(int audioEffectID, int volume)





<p>Set volume for a single audio effect. Both the local play volume and the publish volume are set.</p>
<p>Available since: 1.16.0
Description: Set volume for a single audio effect. Both the local play volume and the publish volume are set.
When to call: The specified <code>audioEffectID</code> is <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/start.md">start</a>.
Restrictions: None.</p>
<ul>
<li><code>audioEffectID</code> ID for the audio effect.</li>
<li><code>volume</code> Volume. <br>Value range: The range is 0 ~ 200. <br>Default value: The default is 100.</li>
</ul>



## Implementation

```dart
Future<void> setVolume(int audioEffectID, int volume);
```







