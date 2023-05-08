


# onNetworkSpeedTestError property







(void Function(int errorCode, [ZegoNetworkSpeedTestType](../../zego_uikit_prebuilt_live_audio_room/ZegoNetworkSpeedTestType.md) type)?) onNetworkSpeedTestError
  
_<span class="feature">read / write</span>_



<p>Network speed test error callback.</p>
<p>Available since: 1.20.0
Description: Network speed test error callback.
Use cases: This function can be used to detect whether the network environment is suitable for pushing/pulling streams with specified bitrates.
When to Trigger: If an error occurs during the speed test, such as: can not connect to speed test server, this callback will be triggered.
Restrictions: None.</p>
<ul>
<li><code>errorCode</code> Network speed test error code. Please refer to error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
<li><code>type</code> Uplink or downlink.</li>
</ul>



## Implementation

```dart
static void Function(int errorCode, ZegoNetworkSpeedTestType type)?
    onNetworkSpeedTestError;
```







