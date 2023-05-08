


# onCapturedSoundLevelInfoUpdate property







(void Function([ZegoSoundLevelInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoSoundLevelInfo-class.md) soundLevelInfo)?) onCapturedSoundLevelInfoUpdate
  
_<span class="feature">read / write</span>_



<p>The local captured audio sound level callback.</p>
<p>Available since: 2.10.0
Description: The local captured audio sound level callback.
Trigger: After you start the sound level monitor by calling <code>startSoundLevelMonitor</code>.
Caution:</p>
<ol>
<li>The callback notification period is the parameter value set when the <code>startSoundLevelMonitor</code> is called.</li>
<li>This callback is a high-frequency callback, and it is recommended not to do complex logic processing inside the callback.
Related APIs: Start sound level monitoring via <code>startSoundLevelMonitor</code>. Monitoring remote played audio sound level by callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteSoundLevelUpdate.md">onRemoteSoundLevelUpdate</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteSoundLevelInfoUpdate.md">onRemoteSoundLevelInfoUpdate</a>.</li>
</ol>
<ul>
<li><code>soundLevelInfo</code> Locally captured sound level value, ranging from 0.0 to 100.0.</li>
</ul>



## Implementation

```dart
static void Function(ZegoSoundLevelInfo soundLevelInfo)?
    onCapturedSoundLevelInfoUpdate;
```







