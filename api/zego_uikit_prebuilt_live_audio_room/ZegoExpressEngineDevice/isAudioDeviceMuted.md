


# isAudioDeviceMuted method








Future&lt;bool> isAudioDeviceMuted
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID)





<p>Check if the audio device is muted.</p>
<p>Only for Windows / macOS / Linux</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceID</code> ID of a device obtained by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md">getAudioDeviceList</a></li>
<li>Returns Whether the audio device is muted; true means the audio device is muted; false means the audio device is not muted.</li>
</ul>



## Implementation

```dart
Future<bool> isAudioDeviceMuted(
    ZegoAudioDeviceType deviceType, String deviceID) async {
  return await ZegoExpressImpl.instance
      .isAudioDeviceMuted(deviceType, deviceID);
}
```







