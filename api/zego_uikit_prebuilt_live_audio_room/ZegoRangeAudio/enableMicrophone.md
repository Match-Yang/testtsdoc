


# enableMicrophone method








Future&lt;void> enableMicrophone
(bool enable)





<p>Turn the microphone on or off.</p>
<p>Available since: 2.11.0
Description: When enable is <code>true</code>, turn on the microphone and push audio stream; when it is <code>false</code>, turn off the microphone and stop pushing audio stream.
Use case: The user turns on or off the microphone to communicate in the room.
Default value: When this function is not called, the microphone is turned off by default.
When to call: After initializing the range audio <code>createRangeAudio</code> and login room <code>loginRoom</code>.
Caution: Turning on the microphone will automatically use the main channel to push the audio stream.
Related callbacks: Get the microphone switch state change through the callback <code>onRangeAudioMicrophoneStateUpdate</code>.</p>
<ul>
<li><code>enable</code> Whether to turn on the microphone.</li>
</ul>



## Implementation

```dart
Future<void> enableMicrophone(bool enable);
```







