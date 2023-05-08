


# startNetworkSpeedTest method








Future&lt;void> startNetworkSpeedTest
([ZegoNetworkSpeedTestConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoNetworkSpeedTestConfig-class.md) config, {int? interval})





<p>Start network speed test. Support set speed test interval。</p>
<p>Available since: 1.20.0
Description: This function supports uplink/downlink network speed test when the network can be connected.
Use cases: This function can be used to detect whether the network environment is suitable for pushing/pulling streams with specified bitrates.
When to call: It needs to be called after <code>loginRoom</code>, and before <code>startPublishingStream</code>. If you call <code>startPublishingStream</code> while speed testing, the speed test will automatically stop.
Restrictions: The maximum allowable test time for a single network speed test is 3 minutes.
Caution: Developers can register <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onNetworkSpeedTestQualityUpdate.md">onNetworkSpeedTestQualityUpdate</a> callback to get the speed test result, which will be triggered every 3 seconds. If an error occurs during the speed test process, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onNetworkSpeedTestError.md">onNetworkSpeedTestError</a> callback will be triggered. If this function is repeatedly called multiple times, the last functioh call's configuration will be used.
Related APIs: Call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineUtilities/stopNetworkSpeedTest.md">stopNetworkSpeedTest</a> to stop network speed test.</p>
<ul>
<li><code>config</code> Network speed test configuration.</li>
<li><code>interval</code> Interval of network speed test. In milliseconds, default is 3000 ms.</li>
</ul>



## Implementation

```dart
Future<void> startNetworkSpeedTest(ZegoNetworkSpeedTestConfig config,
    {int? interval}) async {
  return await ZegoExpressImpl.instance
      .startNetworkSpeedTest(config, interval: interval);
}
```







