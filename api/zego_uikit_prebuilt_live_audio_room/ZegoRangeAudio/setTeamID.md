


# setTeamID method








Future&lt;void> setTeamID
(String teamID)





<p>Set team ID.</p>
<p>Available: since 2.11.0
Description: After setting the team ID, you will be able to communicate with other users of the same team, and the sound will not change with the distance. It is also possible to exit the team by setting an empty string.
Use case: Users join the team or exit the team.
Default value: When this function is not called, no team will be added by default.
When to call: After initializing the range audio <code>createRangeAudio</code>.
Caution: There will be no distance limit for the sounds in the team, and there will be no 3D sound effects.
Restrictions: The team ID will only take effect when <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setRangeAudioMode.md">setRangeAudioMode</a> is called and set to <code>Team</code> mode.</p>
<ul>
<li><code>teamID</code> Team ID, empty to exit the team, a string of up to 64 bytes in length. Support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.</li>
</ul>



## Implementation

```dart
Future<void> setTeamID(String teamID);
```







