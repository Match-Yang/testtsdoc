


# stopNetworkSpeedTest method








Future&lt;void> stopNetworkSpeedTest
()





<p>Stop network speed test.</p>
<p>Available since: 1.20.0
Description: Stop network speed test.
Use cases: This function can be used to detect whether the network environment is suitable for pushing/pulling streams with specified bitrates.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Caution: After the network speed test stopped, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onNetworkSpeedTestQualityUpdate.md">onNetworkSpeedTestQualityUpdate</a> callback will not be triggered.
Related APIs: Call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineUtilities/startNetworkSpeedTest.md">startNetworkSpeedTest</a> to start network speed test.</p>



## Implementation

```dart
Future<void> stopNetworkSpeedTest() async {
  return await ZegoExpressImpl.instance.stopNetworkSpeedTest();
}
```







