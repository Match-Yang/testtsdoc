


# onAutoMixerSoundLevelUpdate property







(void Function(Map&lt;String, double> soundLevels)?) onAutoMixerSoundLevelUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the sound level of any input stream changes in the auto stream mixing process.</p>
<p>Available since: 2.10.0
Description: According to this callback, user can obtain the sound level information of each stream pulled during auto stream mixing.
Use cases: Often used in voice chat room scenarios.Users can use this callback to show which streamer is speaking when an audience pulls a mixed stream.
Trigger: Call <code>startPlayingStream</code> function to pull the stream.
Related APIs: Users can call <code>startAutoMixerTask</code> function to start an auto stream mixing task.Users can call <code>stopAutoMixerTask</code> function to stop an auto stream mixing task.</p>
<ul>
<li><code>soundLevels</code> Sound level hash map, key is the streamID of every single stream in this mixer stream, value is the sound level value of that single stream, value ranging from 0.0 to 100.0.</li>
</ul>



## Implementation

```dart
static void Function(Map<String, double> soundLevels)?
    onAutoMixerSoundLevelUpdate;
```







