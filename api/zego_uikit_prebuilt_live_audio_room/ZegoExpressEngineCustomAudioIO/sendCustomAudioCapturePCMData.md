


# sendCustomAudioCapturePCMData method








Future&lt;void> sendCustomAudioCapturePCMData
(Uint8List data, int dataLength, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sends PCM audio data produced by custom audio capture to the SDK (for the specified channel).</p>
<p>Available since: 1.10.0
Description: Sends the captured audio PCM data to the SDK.
Use cases: 1.The customer needs to obtain input after acquisition from the existing audio stream, audio file, or customized acquisition system, and hand it over to the SDK for transmission. 2.Customers have their own requirements for special sound processing for PCM input sources. After the sound processing, the input will be sent to the SDK for transmission.
When to call: After <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioIO.md">enableCustomAudioIO</a> and publishing stream successfully.
Restrictions: None.
Related APIs: Enable the custom audio IO function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioIO.md">enableCustomAudioIO</a>, and start the push stream <code>startPublishingStream</code>.</p>
<ul>
<li><code>data</code> PCM buffer data.</li>
<li><code>dataLength</code> The total length of the buffer data.</li>
<li><code>param</code> The param of this PCM audio frame.</li>
<li><code>channel</code> Publish channel for capturing audio frames.</li>
</ul>



## Implementation

```dart
Future<void> sendCustomAudioCapturePCMData(
    Uint8List data, int dataLength, ZegoAudioFrameParam param,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance.sendCustomAudioCapturePCMData(
      data, dataLength, param,
      channel: channel);
}
```







