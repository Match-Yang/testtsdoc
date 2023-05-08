


# removePublishCdnUrl method








Future&lt;[ZegoPublisherUpdateCdnUrlResult](../../zego_uikit_prebuilt_live_audio_room/ZegoPublisherUpdateCdnUrlResult-class.md)> removePublishCdnUrl
(String streamID, String targetURL)





<p>Deletes the specified CDN URL, which is used for relaying streams from ZEGO RTC server to CDN.</p>
<p>Available since: 1.1.0
Description: When a CDN forwarding address has been added via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/addPublishCdnUrl.md">addPublishCdnUrl</a>, this function is called when the stream needs to be stopped.
When to call: After calling the <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> function to create the engine, When you don't need to continue publish to the CDN.
Restrictions: When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enablePublishDirectToCDN.md">enablePublishDirectToCDN</a> function is set to true to publish the stream straight to the CDN, then calling this function will have no effect.
Caution: This function does not stop publishing audio and video stream to the ZEGO ZEGO RTC server.
Related APIs: Add URLs that are re-pushed to the CDN <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/addPublishCdnUrl.md">addPublishCdnUrl</a>.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>targetURL</code> CDN relay address, supported address format rtmp.</li>
<li>Returns The execution result of update the relay CDN operation.</li>
</ul>



## Implementation

```dart
Future<ZegoPublisherUpdateCdnUrlResult> removePublishCdnUrl(
    String streamID, String targetURL) async {
  return await ZegoExpressImpl.instance
      .removePublishCdnUrl(streamID, targetURL);
}
```







