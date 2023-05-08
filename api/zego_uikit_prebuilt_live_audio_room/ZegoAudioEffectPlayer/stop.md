


# stop method








Future&lt;void> stop
(int audioEffectID)





<p>Stop playing audio effect.</p>
<p>Available since: 1.16.0
Description: Stop playing the specified audio effect <code>audioEffectID</code>.
When to call: The specified <code>audioEffectID</code> is <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/start.md">start</a>.
Restrictions: None.</p>
<ul>
<li><code>audioEffectID</code> ID for the audio effect.</li>
</ul>



## Implementation

```dart
Future<void> stop(int audioEffectID);
```







