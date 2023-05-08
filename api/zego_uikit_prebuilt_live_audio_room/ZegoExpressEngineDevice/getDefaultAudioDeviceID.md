


# getDefaultAudioDeviceID method








Future&lt;String> getDefaultAudioDeviceID
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType)





<p>Get the device ID of the default audio device.</p>
<p>Only for Windows / macOS / Linux</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li>Returns Default Audio device ID</li>
</ul>



## Implementation

```dart
Future<String> getDefaultAudioDeviceID(ZegoAudioDeviceType deviceType) async {
  return await ZegoExpressImpl.instance.getDefaultAudioDeviceID(deviceType);
}
```







