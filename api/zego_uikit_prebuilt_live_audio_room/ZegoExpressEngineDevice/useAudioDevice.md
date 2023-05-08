


# useAudioDevice method








Future&lt;void> useAudioDevice
([ZegoAudioDeviceType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID)





<p>Chooses to use the specified audio device.</p>
<p>Available since: 1.0.0
Description: Chooses to use the specified audio device.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> and before call <code>startPublishingStream</code> or <code>startPlayingStream</code>.
Restrictions: Only supports Windows / macOS / Linux</p>
<ul>
<li><code>deviceType</code> Audio device type</li>
<li><code>deviceID</code> ID of a device obtained by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md">getAudioDeviceList</a></li>
</ul>



## Implementation

```dart
Future<void> useAudioDevice(
    ZegoAudioDeviceType deviceType, String deviceID) async {
  return await ZegoExpressImpl.instance.useAudioDevice(deviceType, deviceID);
}
```







