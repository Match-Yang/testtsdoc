


# getAudioDeviceVolume method








Future&lt;int> getAudioDeviceVolume
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID)





<p>Get volume for the specified audio device.</p>
<p>Get volume for the specified audio device. Only for Windows / macOS / Linux</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceID</code> ID of a device obtained by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md">getAudioDeviceList</a></li>
<li>Returns Device volume</li>
</ul>



## Implementation

```dart
Future<int> getAudioDeviceVolume(
    ZegoAudioDeviceType deviceType, String deviceID) async {
  return await ZegoExpressImpl.instance
      .getAudioDeviceVolume(deviceType, deviceID);
}
```







