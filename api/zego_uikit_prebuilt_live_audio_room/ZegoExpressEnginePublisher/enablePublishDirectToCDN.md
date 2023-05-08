


# enablePublishDirectToCDN method








Future&lt;void> enablePublishDirectToCDN
(bool enable, {[ZegoCDNConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig-class.md)? config, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Whether to directly push to CDN (without going through the ZEGO RTC server), for the specified channel.</p>
<p>Available since: 1.5.0
Description: Whether to publish streams directly from the client to CDN without passing through Zego RTC server.
Use cases: It is often used in large-scale live broadcast scenes that do not have particularly high requirements for delay.
Default value: The default is false, and direct push is not enabled.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before starting to push the stream <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>.
Caution: The Direct Push CDN feature does not pass through the ZEGO Real-Time Audio and Video Cloud during network transmission, so you cannot use ZEGO's ultra-low latency audio and video services.
Related APIs: Dynamic re-push to CDN function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/addPublishCdnUrl.md">addPublishCdnUrl</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/removePublishCdnUrl.md">removePublishCdnUrl</a>.</p>
<ul>
<li><code>enable</code> Whether to enable direct publish CDN, true: enable direct publish CDN, false: disable direct publish CDN.</li>
<li><code>config</code> CDN configuration, if null, use Zego's background default configuration.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> enablePublishDirectToCDN(bool enable,
    {ZegoCDNConfig? config, ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .enablePublishDirectToCDN(enable, config: config, channel: channel);
}
```







