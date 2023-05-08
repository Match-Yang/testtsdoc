


# onAudioDeviceStateChanged property







(void Function([ZegoUpdateType](../../zego_uikit_prebuilt_live_audio_room/ZegoUpdateType.md) updateType, [ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, [ZegoDeviceInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md) deviceInfo)?) onAudioDeviceStateChanged
  
_<span class="feature">read / write</span>_



<p>The callback triggered when there is a change to audio devices (i.e. new device added or existing device deleted).</p>
<p>Only supports desktop.
This callback is triggered when an audio device is added or removed from the system. By listening to this callback, users can update the sound collection or output using a specific device when necessary.</p>
<ul>
<li><code>updateType</code> Update type (add/delete)</li>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceInfo</code> Audio device information</li>
</ul>



## Implementation

```dart
static void Function(
    ZegoUpdateType updateType,
    ZegoAudioDeviceType deviceType,
    ZegoDeviceInfo deviceInfo)? onAudioDeviceStateChanged;
```







