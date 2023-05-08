


# getAudioDeviceList method








Future&lt;List&lt;[ZegoDeviceInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md)>> getAudioDeviceList
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType)





<p>Gets a list of audio devices.</p>
<p>Only for Windows / macOS / Web</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li>Returns Audo device List</li>
</ul>



## Implementation

```dart
Future<List<ZegoDeviceInfo>> getAudioDeviceList(
    ZegoAudioDeviceType deviceType) async {
  return await ZegoExpressImpl.instance.getAudioDeviceList(deviceType);
}
```







