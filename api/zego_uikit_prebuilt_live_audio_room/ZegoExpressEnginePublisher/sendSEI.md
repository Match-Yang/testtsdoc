


# sendSEI method








Future&lt;void> sendSEI
(Uint8List data, int dataLength, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sends Supplemental Enhancement Information.</p>
<p>Available since: 1.1.0
Description: While pushing the stream to transmit the audio and video stream data, the stream media enhancement supplementary information is sent to synchronize some other additional information.
Use cases: Generally used in scenes such as synchronizing music lyrics or precise video layout, you can choose to send SEI.
When to call: After starting to push the stream <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>.
Restrictions: Do not exceed 30 times per second, and the SEI data length is limited to 4096 bytes.
Caution: Since the SEI information follows the video frame, there may be frame loss due to network problems, so the SEI information may also be lost. In order to solve this situation, it should be sent several times within the restricted frequency.
Related APIs: After the pusher sends the SEI, the puller can obtain the SEI content by monitoring the callback of <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRecvSEI.md">onPlayerRecvSEI</a>.</p>
<ul>
<li><code>data</code> SEI data.</li>
<li><code>dataLength</code> SEI data length.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> sendSEI(Uint8List data, int dataLength,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .sendSEI(data, dataLength, channel: channel);
}
```







