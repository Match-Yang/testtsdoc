


# sendAudioSideInfo method








Future&lt;void> sendAudioSideInfo
(Uint8List data, double timeStampMs, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Send audio side information.</p>
<p>Available since: 2.19.0
Description: While streaming audio data, send audio side information to synchronize some additional information.
Use cases: In the carousel scene, the audio data channel is required to carry accompanying information, such as timestamps to help align the accompaniment, and the need to know who the user is currently singing, whether to amplify the volume, and so on.
When to call: After starting to push the stream <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>.
Restrictions: 1. This function is only valid when publishing stream to the Zego RTC server and it also doesn't work when retweeting the stream from the RTC server to the CDN. 2. The audio side information data length is limited to 1024 bytes.
Caution: 1. Audio side information is driven by audio data, so audio data must be pushed (audio side information may be lost when the DTX function is enabled via the interface <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setEngineConfig.md">setEngineConfig</a>). 2. Due to network issues, audio side information may be lost, and the SDK is responsible for transmission but does not guarantee reliability.
Related APIs: After the pusher sends the side information, the puller can obtain the side information content by monitoring the callback of <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRecvAudioSideInfo.md">onPlayerRecvAudioSideInfo</a>.</p>
<ul>
<li><code>data</code> Audio side info data.</li>
<li><code>timeStampMs</code> timeStampMs, derived from custom audio processing, in milliseconds. If you fill in 0, it is sent along with the frame that is currently ready to be sent.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> sendAudioSideInfo(Uint8List data, double timeStampMs,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .sendAudioSideInfo(data, timeStampMs, channel: channel);
}
```







