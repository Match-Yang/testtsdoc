


# onPlayerAudioData property







(void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, String streamID)?) onPlayerAudioData
  
_<span class="feature">read / write</span>_



<p>The callback for obtaining the audio data of each stream.</p>
<p>Available: Since 1.1.0
Description: This function will call back the data corresponding to each playing stream. Different from <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlaybackAudioData.md">onPlaybackAudioData</a>, the latter is the mixed data of all playing streams. If developers need to process a piece of data separately, they can use this callback.
When to trigger: On the premise of calling <code>setAudioDataHandler</code> to set up listening for this callback, calling <code>startAudioDataObserver</code> to set the mask 0x08 that is 1 &lt;&lt; 3, and this callback will be triggered when the SDK audio and video engine starts to play the stream.
Restrictions: None.
Caution: This callback is a high-frequency callback, please do not perform time-consuming operations in this callback.</p>
<ul>
<li><code>data</code> Audio data in PCM format.</li>
<li><code>dataLength</code> Length of the data.</li>
<li><code>param</code> Parameters of the audio frame.</li>
<li><code>streamID</code> Corresponding stream ID.</li>
</ul>



## Implementation

```dart
static void Function(Uint8List data, int dataLength,
    ZegoAudioFrameParam param, String streamID)? onPlayerAudioData;
```







