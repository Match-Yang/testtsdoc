


# onAudioDeviceVolumeChanged property







(void Function([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID, int volume)?) onAudioDeviceVolumeChanged
  
_<span class="feature">read / write</span>_



<p>The callback triggered when there is a change of the volume for the audio devices.</p>
<p>Available since: 1.0.0
Description: This callback is used to receive audio device volume change events.
When to trigger: The callback triggered when there is a change of the volume fo the audio devices.
Restrictions: None
Platform differences: Only supports Windows and macOS.</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceID</code> Audio device ID</li>
<li><code>volume</code> audio device volume</li>
</ul>



## Implementation

```dart
static void Function(
        ZegoAudioDeviceType deviceType, String deviceID, int volume)?
    onAudioDeviceVolumeChanged;
```







