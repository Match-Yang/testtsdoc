


# muteAudioDevice method








Future&lt;void> muteAudioDevice
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID, bool mute)





<p>Mutes or unmutes the audio device.</p>
<p>Only for Windows / macOS / Linux</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceID</code> ID of a device obtained by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md">getAudioDeviceList</a></li>
<li><code>mute</code> Whether to mute the audio device; true means to mute the audio device; false means to unmute the audio device.</li>
</ul>



## Implementation

```dart
Future<void> muteAudioDevice(
    ZegoAudioDeviceType deviceType, String deviceID, bool mute) async {
  return await ZegoExpressImpl.instance
      .muteAudioDevice(deviceType, deviceID, mute);
}
```







