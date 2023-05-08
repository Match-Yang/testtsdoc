


# startAudioDeviceVolumeMonitor method








Future&lt;void> startAudioDeviceVolumeMonitor
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID)





<p>Turn on audio device volume monitoring.</p>
<p>Only for Windows / macOS / Linux</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceID</code> ID of a device obtained by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md">getAudioDeviceList</a></li>
</ul>



## Implementation

```dart
Future<void> startAudioDeviceVolumeMonitor(
    ZegoAudioDeviceType deviceType, String deviceID) async {
  return await ZegoExpressImpl.instance
      .startAudioDeviceVolumeMonitor(deviceType, deviceID);
}
```







