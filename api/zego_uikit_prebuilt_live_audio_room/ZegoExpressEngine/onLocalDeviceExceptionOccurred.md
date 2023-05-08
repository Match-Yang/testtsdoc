


# onLocalDeviceExceptionOccurred property







(void Function([ZegoDeviceExceptionType](../../zego_uikit_prebuilt_live_audio_room/ZegoDeviceExceptionType.md) exceptionType, [ZegoDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoDeviceType.md) deviceType, String deviceID)?) onLocalDeviceExceptionOccurred
  
_<span class="feature">read / write</span>_



<p>The callback triggered when a local device exception occurred.</p>
<p>Available since: 2.15.0
Description: The callback triggered when a local device exception occurs.
Trigger: This callback is triggered when the function of the local audio or video device is abnormal.</p>
<ul>
<li><code>exceptionType</code> The type of the device exception.</li>
<li><code>deviceType</code> The type of device where the exception occurred.</li>
<li><code>deviceID</code> Device ID. Currently, only desktop devices are supported to distinguish different devices; for mobile devices, this parameter will return an empty string.</li>
</ul>



## Implementation

```dart
static void Function(
    ZegoDeviceExceptionType exceptionType,
    ZegoDeviceType deviceType,
    String deviceID)? onLocalDeviceExceptionOccurred;
```







