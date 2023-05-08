


# setAudioDeviceVolume method








Future&lt;void> setAudioDeviceVolume
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID, int volume)





<p>Set volume for the specified audio device.</p>
<p>The direct operating system device may fail due to system restrictions. Please use <code>setCaptureVolume</code> and <code>setPlayVolume</code> first to adjust the volume of publish and play streams.
Only for Windows / macOS / Linux</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceID</code> ID of a device obtained by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md">getAudioDeviceList</a></li>
<li><code>volume</code> Device volume</li>
</ul>



## Implementation

```dart
Future<void> setAudioDeviceVolume(
    ZegoAudioDeviceType deviceType, String deviceID, int volume) async {
  return await ZegoExpressImpl.instance
      .setAudioDeviceVolume(deviceType, deviceID, volume);
}
```







