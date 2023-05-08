


# sendCustomAudioCaptureAACData method








Future&lt;void> sendCustomAudioCaptureAACData
(Uint8List data, int dataLength, int configLength, int referenceTimeMillisecond, int samples, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sends AAC audio data produced by custom audio capture to the SDK (for the specified channel).</p>
<p>Available since: 2.20.0
Description: Sends the captured audio AAC data to the SDK.
Use cases: The customer needs to obtain input after acquisition from the existing audio stream, audio file, or customized acquisition system, and hand it over to the SDK for transmission.
When to call: After <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioIO.md">enableCustomAudioIO</a> and publishing stream successfully.
Restrictions: None.
Related APIs: Enable the custom audio IO function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioIO.md">enableCustomAudioIO</a>, and start the push stream <code>startPublishingStream</code>.</p>
<ul>
<li><code>data</code> AAC buffer data.</li>
<li><code>dataLength</code> The total length of the buffer data.</li>
<li><code>configLength</code> The length of AAC specific config (Note: The AAC encoded data length is 'encodedLength = dataLength - configLength').Value range: <code>0,64</code></li>
<li><code>referenceTimeMillisecond</code> The UNIX timestamp of this AAC audio frame in millisecond.</li>
<li><code>samples</code> The number of samples for this AAC audio frame.Value range: <code>480,512,1024,1960,2048</code>.</li>
<li><code>param</code> The param of this AAC audio frame.</li>
<li><code>channel</code> Publish channel for capturing audio frames.</li>
</ul>



## Implementation

```dart
Future<void> sendCustomAudioCaptureAACData(
    Uint8List data,
    int dataLength,
    int configLength,
    int referenceTimeMillisecond,
    int samples,
    ZegoAudioFrameParam param,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance.sendCustomAudioCaptureAACData(data,
      dataLength, configLength, referenceTimeMillisecond, samples, param,
      channel: channel);
}
```







