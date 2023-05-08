


# setAudioDeviceMode method








Future&lt;void> setAudioDeviceMode
([ZegoAudioDeviceMode](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceMode.md) deviceMode)





<p>Set the audio device mode.</p>
<p>Available since: 2.22.0
Description: Select audio equipment mode according to the need of the scene (only supported by Android and iOS).
Use cases: In the case of KTV, the General mode must be used, but in the language room, the Communication2 or Communication3 mode is required in order to avoid the sound of third-party music being collected. For details on how to set the audio device mode, see <a href="https://doc-zh.zego.im/faq/AudioDeviceMod?product=ExpressVideo&amp;platform=macos">https://doc-zh.zego.im/faq/AudioDeviceMod?product=ExpressVideo&amp;platform=macos</a>
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution: This interface triggers startup switchover of the device. You are advised not to invoke this interface frequently to avoid unnecessary overhead and hardware problems. This interface may cause the volume mode to switch between call and media. If the media volume is inconsistent with the call volume, the volume may change.</p>
<ul>
<li><code>deviceMode</code> Audio device mode</li>
</ul>



## Implementation

```dart
Future<void> setAudioDeviceMode(ZegoAudioDeviceMode deviceMode) async {
  return await ZegoExpressImpl.instance.setAudioDeviceMode(deviceMode);
}
```







