


# onCapturedSoundLevelUpdate property







(void Function(double soundLevel)?) onCapturedSoundLevelUpdate
  
_<span class="feature">read / write</span>_



<p>The local captured audio sound level callback.</p>
<p>Available since: 1.1.0
Description: The local captured audio sound level callback.
Trigger: After you start the sound level monitor by calling <code>startSoundLevelMonitor</code>.
Caution:</p>
<ol>
<li>The callback notification period is the parameter value set when the <code>startSoundLevelMonitor</code> is called. The callback value is the default value of 0 When you have not called the interface <code>startPublishingStream</code> and <code>startPreview</code>.</li>
<li>This callback is a high-frequency callback, and it is recommended not to do complex logic processing inside the callback.
Related APIs: Start sound level monitoring via <code>startSoundLevelMonitor</code>. Monitoring remote played audio sound level by callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteSoundLevelUpdate.md">onRemoteSoundLevelUpdate</a></li>
</ol>
<ul>
<li><code>soundLevel</code> Locally captured sound level value, ranging from 0.0 to 100.0.</li>
</ul>



## Implementation

```dart
static void Function(double soundLevel)? onCapturedSoundLevelUpdate;
```







