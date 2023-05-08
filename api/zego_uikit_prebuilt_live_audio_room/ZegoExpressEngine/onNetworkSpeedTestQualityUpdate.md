


# onNetworkSpeedTestQualityUpdate property







(void Function([ZegoNetworkSpeedTestQuality](../../zego_uikit_prebuilt_live_audio_room/ZegoNetworkSpeedTestQuality-class.md) quality, [ZegoNetworkSpeedTestType](../../zego_uikit_prebuilt_live_audio_room/ZegoNetworkSpeedTestType.md) type)?) onNetworkSpeedTestQualityUpdate
  
_<span class="feature">read / write</span>_



<p>Network speed test quality callback.</p>
<p>Available since: 1.20.0
Description: Network speed test quality callback when the network can be connected.
Use cases: This function can be used to detect whether the network environment is suitable for pushing/pulling streams with specified bitrates.
When to Trigger: After call <code>startNetworkSpeedTest</code> start network speed test, this callback will be triggered. The trigger period is determined by the parameter value specified by call <code>startNetworkSpeedTest</code>, default value is 3 seconds
Restrictions: None.
Caution: When error occurred during network speed test or <code>stopNetworkSpeedTest</code> called, this callback will not be triggered.</p>
<ul>
<li><code>quality</code> Network speed test quality.</li>
<li><code>type</code> Uplink or downlink.</li>
</ul>



## Implementation

```dart
static void Function(
        ZegoNetworkSpeedTestQuality quality, ZegoNetworkSpeedTestType type)?
    onNetworkSpeedTestQualityUpdate;
```







