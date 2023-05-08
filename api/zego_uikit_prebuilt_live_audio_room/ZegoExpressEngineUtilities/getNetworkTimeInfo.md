


# getNetworkTimeInfo method








Future&lt;[ZegoNetworkTimeInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoNetworkTimeInfo-class.md)> getNetworkTimeInfo
()





<p>Obtain synchronization network time information.</p>
<p>Available since: 2.9.0
Description: Obtain synchronization network time(NTP), including timestamp and maximum deviation.
Use cases: When performing multi-terminal synchronization behaviors, network time synchronization is required.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.</p>



## Implementation

```dart
Future<ZegoNetworkTimeInfo> getNetworkTimeInfo() async {
  return await ZegoExpressImpl.instance.getNetworkTimeInfo();
}
```







