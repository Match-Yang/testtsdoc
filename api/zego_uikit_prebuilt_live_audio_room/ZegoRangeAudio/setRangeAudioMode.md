


# setRangeAudioMode method








Future&lt;void> setRangeAudioMode
([ZegoRangeAudioMode](../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudioMode.md) mode)





<p>Set range audio mode.</p>
<p>Available since: 2.11.0
Description: The audio mode can be set to <code>World</code> mode or <code>Team</code> mode.
Use case: The user can choose to chat with everyone in the <code>World</code> mode (with distance limitation), or to communicate within the team in the <code>Team</code> mode (without distance limitation).
Default value: If this function is not called, the <code>World</code> mode is used by default.
When to call: After initializing the range audio <code>createRangeAudio</code>.
Related APIs: In the <code>World</code> mode, you can set the sound receiving range <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setAudioReceiveRange.md">setAudioReceiveRange</a>, in the <code>Team</code> mode, you need to set <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setTeamID.md">setTeamID</a> to join the corresponding team to hear the voice in the team.</p>
<ul>
<li><code>mode</code> The range audio mode.</li>
</ul>



## Implementation

```dart
Future<void> setRangeAudioMode(ZegoRangeAudioMode mode);
```







