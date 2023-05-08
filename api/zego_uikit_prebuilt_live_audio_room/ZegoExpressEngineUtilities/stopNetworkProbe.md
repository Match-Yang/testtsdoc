


# stopNetworkProbe method








Future&lt;void> stopNetworkProbe
()





<p>Stop network probe.</p>
<p>Available since: 2.3.0
Description: Stop network probe.
Use cases: Before pushing and pulling the stream, detect and locate some possible network problems.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related APIs: Call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineUtilities/startNetworkProbe.md">startNetworkProbe</a> to start network probe.</p>



## Implementation

```dart
Future<void> stopNetworkProbe() async {
  return await ZegoExpressImpl.instance.stopNetworkProbe();
}
```







