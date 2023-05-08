


# isCameraFocusSupported method








Future&lt;bool> isCameraFocusSupported
({[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Whether the camera supports focusing.</p>
<p>Available since: 2.14.0
Description: Whether the camera supports focusing.
Trigger: Called after turn on preview <code>startPreivew</code>.
Caution: Need to start the camera successfully.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>channel</code> Publishing stream channel</li>
<li>Returns Whether to support focus, support is true, not support is false.</li>
</ul>



## Implementation

```dart
Future<bool> isCameraFocusSupported({ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .isCameraFocusSupported(channel: channel);
}
```







