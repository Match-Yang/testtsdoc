


# onRemoteSoundLevelUpdate property







(void Function(Map&lt;String, double> soundLevels)?) onRemoteSoundLevelUpdate
  
_<span class="feature">read / write</span>_



<p>The remote playing streams audio sound level callback.</p>
<p>Available since: 1.1.0
Description: The remote playing streams audio sound level callback.
Trigger: After you start the sound level monitor by calling <code>startSoundLevelMonitor</code>, you are in the state of playing the stream <code>startPlayingStream</code>.
Caution: The callback notification period is the parameter value set when the <code>startSoundLevelMonitor</code> is called.
Related APIs: Start sound level monitoring via <code>startSoundLevelMonitor</code>. Monitoring local captured audio sound by callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedSoundLevelUpdate.md">onCapturedSoundLevelUpdate</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedSoundLevelInfoUpdate.md">onCapturedSoundLevelInfoUpdate</a>.</p>
<ul>
<li><code>soundLevels</code> Remote sound level hash map, key is the streamID, value is the sound level value of the corresponding streamID, value ranging from 0.0 to 100.0.</li>
</ul>



## Implementation

```dart
static void Function(Map<String, double> soundLevels)?
    onRemoteSoundLevelUpdate;
```







