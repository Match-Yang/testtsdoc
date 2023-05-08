


# enableSpeaker method








Future&lt;void> enableSpeaker
(bool enable)





<p>Turn the speaker on or off.</p>
<p>Available since: 2.11.0
Description: When enable is <code>true</code>, turn on the speaker and play audio stream; when it is <code>false</code>, turn off the speaker and stop playing audio stream.
Use case: The user turns on or off the speaker to communicate in the room.
Default value: When this function is not called, the speaker is turned off by default.
When to call: After initializing the range audio <code>createRangeAudio</code> and login room <code>loginRoom</code>.
Caution: Turning on the speaker will automatically pull the audio stream in the room.</p>
<ul>
<li><code>enable</code> Whether to turn on the speaker.</li>
</ul>



## Implementation

```dart
Future<void> enableSpeaker(bool enable);
```







