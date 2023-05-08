


# enableH265EncodeFallback method








Future&lt;void> enableH265EncodeFallback
(bool enable)





<p>Whether to enable H.265 encoding to automatically downgrade to H.264 encoding.</p>
<p>Available since: 2.12.0
Description: When using H.265 encoding to push the stream, whether to enable the strategy of automatically degrading H.265 encoding to H.264 encoding under abnormal circumstances.After enabling automatic downgrade, when H.265 encoding is not supported or H.265 encoding fails, the SDK will try to downgrade and use H.264 encoding to push the stream.After turning off automatic downgrade, when H.265 encoding is not supported or H.265 encoding fails, the direct streaming fails.
Use cases: In the Co-hosting and Showroom Live Streaming scenarios, use H265 encoding to push the stream to save CDN traffic without degrading the picture quality.
Default Value: When this interface is not called, the default is yes, which means that H.265 encoding is turned on and automatically downgraded to H.264 encoding.
When to call: After creating the engine, call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a> function before pushing the stream.
Related callbacks: When the H.265 encoding is automatically downgraded to the H.264 encoding strategy, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherVideoEncoderChanged.md">onPublisherVideoEncoderChanged</a> callback will be triggered when the encoding method changes.
Caution: When downgrading from H.265 to H.264 encoding occurs during the streaming process, if you are recording local video or cloud recording, multiple recording files will be generated, which needs to be dealt with.</p>
<ul>
<li><code>enable</code> Whether to enable H.265 coding automatically fallback to H.264 coding, true: enable, false: disable, and the default value is true</li>
</ul>



## Implementation

```dart
Future<void> enableH265EncodeFallback(bool enable) async {
  return await ZegoExpressImpl.instance.enableH265EncodeFallback(enable);
}
```







