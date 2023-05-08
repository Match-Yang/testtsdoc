


# stopPreview method








Future&lt;void> stopPreview
({[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Stops the local preview (for the specified channel).</p>
<p>Available since: 1.1.0
Description: This function can be called to stop the preview when the preview is not needed locally.
Caution: Stopping the preview will not affect the publish stream and playing stream functions.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>channel</code> Publish stream channel</li>
</ul>



## Implementation

```dart
Future<void> stopPreview({ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance.stopPreview(channel: channel);
}
```







