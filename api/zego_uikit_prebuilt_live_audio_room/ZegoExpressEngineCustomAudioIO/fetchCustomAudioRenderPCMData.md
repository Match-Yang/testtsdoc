


# fetchCustomAudioRenderPCMData method








Future&lt;void> fetchCustomAudioRenderPCMData
(Uint8List data, int dataLength, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)





<p>Fetches PCM audio data of the remote stream from the SDK for custom audio rendering.</p>
<p>Available since: 1.10.0
Description: Fetches PCM audio data of the remote stream from the SDK for custom audio rendering, it is recommended to use the system framework to periodically invoke this function to drive audio data rendering.
Use cases: When developers have their own rendering requirements, such as special applications or processing and rendering of the original PCM data that are pulled, it is recommended to use the custom audio rendering function of the SDK.
When to call: After <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioIO.md">enableCustomAudioIO</a> and playing stream successfully.
Restrictions: None.
Related APIs: Enable the custom audio IO function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioIO.md">enableCustomAudioIO</a>, and start the play stream <code>startPlayingStream</code>.</p>
<ul>
<li><code>data</code> A block of memory for storing audio PCM data that requires user to manage the memory block's lifecycle, the SDK will copy the audio frame rendering data to this memory block.</li>
<li><code>dataLength</code> The length of the audio data to be fetch this time (dataLength = duration * sampleRate * channels * 2(16 bit depth i.e. 2 Btye)).</li>
<li><code>param</code> Specify the parameters of the fetched audio frame. sampleRate in ZegoAudioFrameParam must assignment</li>
</ul>



## Implementation

```dart
Future<void> fetchCustomAudioRenderPCMData(
    Uint8List data, int dataLength, ZegoAudioFrameParam param) async {
  return await ZegoExpressImpl.instance
      .fetchCustomAudioRenderPCMData(data, dataLength, param);
}
```







