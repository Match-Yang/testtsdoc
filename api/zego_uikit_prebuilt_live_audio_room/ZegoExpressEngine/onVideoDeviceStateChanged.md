


# onVideoDeviceStateChanged property







(void Function([ZegoUpdateType](../../zego_uikit_prebuilt_live_audio_room/ZegoUpdateType.md) updateType, [ZegoDeviceInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md) deviceInfo)?) onVideoDeviceStateChanged
  
_<span class="feature">read / write</span>_



<p>The callback triggered when there is a change to video devices (i.e. new device added or existing device deleted).</p>
<p>Available since: 1.0.0
Description: By listening to this callback, users can update the video capture using a specific device when necessary.
When to trigger: This callback is triggered when a video device is added or removed from the system.
Restrictions: None
Platform differences: Only supports Windows and macOS.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>updateType</code> Update type (add/delete)</li>
<li><code>deviceInfo</code> Audio device information</li>
</ul>



## Implementation

```dart
static void Function(ZegoUpdateType updateType, ZegoDeviceInfo deviceInfo)?
    onVideoDeviceStateChanged;
```







