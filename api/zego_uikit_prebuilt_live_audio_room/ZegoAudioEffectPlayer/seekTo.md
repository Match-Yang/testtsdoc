


# seekTo method








Future&lt;[ZegoAudioEffectPlayerSeekToResult](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayerSeekToResult-class.md)> seekTo
(int audioEffectID, int millisecond)





<p>Set the specified playback progress.</p>
<p>Available since: 1.16.0
Description: Set the specified audio effect playback progress. Unit is millisecond.
When to call: The specified <code>audioEffectID</code> is<a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/start.md">start</a>, and not finished.
Restrictions: None.</p>
<ul>
<li><code>audioEffectID</code> ID for the audio effect.</li>
<li><code>millisecond</code> Point in time of specified playback progress.</li>
<li>Returns Result for audio effect player seek to playback progress</li>
</ul>



## Implementation

```dart
Future<ZegoAudioEffectPlayerSeekToResult> seekTo(
    int audioEffectID, int millisecond);
```







