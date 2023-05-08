


# stopAudioDeviceVolumeMonitor method








Future&lt;void> stopAudioDeviceVolumeMonitor
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID)





<p>Turn off audio device volume monitoring. Only for Windows/macOS.</p>
<p>Only for Windows / macOS / Linux</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceID</code> ID of a device obtained by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md">getAudioDeviceList</a></li>
</ul>



## Implementation

```dart
Future<void> stopAudioDeviceVolumeMonitor(
    ZegoAudioDeviceType deviceType, String deviceID) async {
  return await ZegoExpressImpl.instance
      .stopAudioDeviceVolumeMonitor(deviceType, deviceID);
}
```







