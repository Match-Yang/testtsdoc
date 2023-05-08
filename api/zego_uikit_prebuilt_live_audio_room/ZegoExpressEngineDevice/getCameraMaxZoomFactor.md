


# getCameraMaxZoomFactor method








Future&lt;double> getCameraMaxZoomFactor
({[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Get the maximum zoom factor of the camera.</p>
<p>Available since: 1.20.0
Description: Set the camera zoom factor. Every time the camera is restarted, the camera zoom factor will be restored to its initial value.
When to call: This is only available after the camera has been successfully started, and can generally be called when the captured first frame is received <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherCapturedVideoFirstFrame.md">onPublisherCapturedVideoFirstFrame</a> callback.
Restrictions: None.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>channel</code> Publishing stream channel</li>
<li>Returns The maximum zoom factor of the camera.</li>
</ul>



## Implementation

```dart
Future<double> getCameraMaxZoomFactor({ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .getCameraMaxZoomFactor(channel: channel);
}
```







