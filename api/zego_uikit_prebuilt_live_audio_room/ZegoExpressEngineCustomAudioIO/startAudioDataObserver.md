


# startAudioDataObserver method








Future&lt;void> startAudioDataObserver
(int observerBitMask, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)





<p>Enable audio data observering.</p>
<p>Available since: 1.1.0
Description: When custom audio processing is turned on, use this function to turn on audio data callback monitoring.
Use cases: When develop need to monitor the original audio.
When to call: After creating the engine.
Restrictions: None.
Caution: This api will start the media engine and occupy the microphone device.</p>
<ul>
<li><code>observerBitMask</code> The callback function bitmask marker for receive audio data, refer to enum <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioDataCallbackBitMask-class.md">ZegoAudioDataCallbackBitMask</a>, when this param converted to binary, 0b01 that means 1 &lt;&lt; 0 for triggering <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedAudioData.md">onCapturedAudioData</a>, 0x10 that means 1 &lt;&lt; 1 for triggering <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlaybackAudioData.md">onPlaybackAudioData</a>, 0x100 that means 1 &lt;&lt; 2 for triggering <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMixedAudioData.md">onMixedAudioData</a>, 0x1000 that means 1 &lt;&lt; 3 for triggering <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerAudioData.md">onPlayerAudioData</a>. The masks can be combined to allow different callbacks to be triggered simultaneously.</li>
<li><code>param</code> param of audio frame.</li>
</ul>



## Implementation

```dart
Future<void> startAudioDataObserver(
    int observerBitMask, ZegoAudioFrameParam param) async {
  return await ZegoExpressImpl.instance
      .startAudioDataObserver(observerBitMask, param);
}
```







