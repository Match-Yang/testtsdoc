


# useVideoDevice method








Future&lt;void> useVideoDevice
(String deviceID, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Chooses to use the specified video device (for the specified channel).</p>
<p>When to call: After <code>startPreview</code> or <code>startPublishingStream</code>.
Caution: Only for Windows / macOS / Web.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>deviceID</code> ID of a device obtained by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getVideoDeviceList.md">getVideoDeviceList</a></li>
<li><code>channel</code> Publishing stream channel</li>
</ul>



## Implementation

```dart
Future<void> useVideoDevice(String deviceID,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .useVideoDevice(deviceID, channel: channel);
}
```







