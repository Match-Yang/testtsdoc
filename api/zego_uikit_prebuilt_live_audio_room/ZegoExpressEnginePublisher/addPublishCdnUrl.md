


# addPublishCdnUrl method








Future&lt;[ZegoPublisherUpdateCdnUrlResult](../../zego_uikit_prebuilt_live_audio_room/ZegoPublisherUpdateCdnUrlResult-class.md)> addPublishCdnUrl
(String streamID, String targetURL)





<p>Adds a target CDN URL to which the stream will be relayed from ZEGO RTC server.</p>
<p>Available since: 1.1.0
Description: Forward audio and video streams from ZEGO RTC servers to custom CDN content distribution networks with high latency but support for high concurrent pull streams.
Use cases: 1. It is often used in large-scale live broadcast scenes that do not have particularly high requirements for delay. 2. Since ZEGO RTC server itself can be configured to support CDN(content distribution networks), this function is mainly used by developers who have CDN content distribution services themselves. 3. This function supports dynamic relay to the CDN content distribution network, so developers can use this function as a disaster recovery solution for CDN content distribution services.
When to call: After calling the <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> function to create the engine.
Restrictions: When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enablePublishDirectToCDN.md">enablePublishDirectToCDN</a> function is set to true to publish the stream straight to the CDN, then calling this function will have no effect.
Caution: Removing URLs retweeted to CDN requires calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/removePublishCdnUrl.md">removePublishCdnUrl</a>, calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/stopPublishingStream.md">stopPublishingStream</a> will not remove URLs publish to CDN.
Related APIs: Remove URLs that are re-pushed to the CDN <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/removePublishCdnUrl.md">removePublishCdnUrl</a>.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>targetURL</code> CDN relay address, supported address format is rtmp, rtmps.</li>
<li>Returns The execution result of update the relay CDN operation.</li>
</ul>



## Implementation

```dart
Future<ZegoPublisherUpdateCdnUrlResult> addPublishCdnUrl(
    String streamID, String targetURL) async {
  return await ZegoExpressImpl.instance.addPublishCdnUrl(streamID, targetURL);
}
```







