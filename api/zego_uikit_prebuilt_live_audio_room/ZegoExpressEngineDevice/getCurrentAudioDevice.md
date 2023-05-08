


# getCurrentAudioDevice method








Future&lt;[ZegoDeviceInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md)> getCurrentAudioDevice
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType)





<p>Get the audio device information currently in use.</p>
<p>Available since: 2.12.0
Description: Get the audio device information currently in use.
Use cases: Used for scenes that need to manually switch between multiple audio devices.
When to call: Called this function after calling <code>startPublishingStream</code> or <code>startPreview</code>.
Restrictions: Only supports Windows and macOS.
Related APIs: The default audio device ID can be obtained through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getDefaultAudioDeviceID.md">getDefaultAudioDeviceID</a>.</p>
<ul>
<li><code>deviceType</code> Audio device type.Required:Yes.</li>
<li>Returns Audio device information.</li>
</ul>



## Implementation

```dart
Future<ZegoDeviceInfo> getCurrentAudioDevice(
    ZegoAudioDeviceType deviceType) async {
  return await ZegoExpressImpl.instance.getCurrentAudioDevice(deviceType);
}
```







