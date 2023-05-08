


# setCameraFocusMode method








Future&lt;void> setCameraFocusMode
([ZegoCameraFocusMode](../../zego_uikit_prebuilt_live_audio_room/ZegoCameraFocusMode.md) mode, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set the camera focus mode.</p>
<p>Available since: 2.14.0
Description: Set the camera focus mode.
Trigger: Called after turn on preview <code>startPreivew</code>.
Restrictions: Currently only supports iOS and Android platforms.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>mode</code> focus mode.</li>
<li><code>channel</code> Publishing stream channel</li>
</ul>



## Implementation

```dart
Future<void> setCameraFocusMode(ZegoCameraFocusMode mode,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setCameraFocusMode(mode, channel: channel);
}
```







