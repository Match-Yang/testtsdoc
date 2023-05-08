


# onAlignedAudioAuxData property







(void Function(Uint8List data, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)?) onAlignedAudioAuxData
  
_<span class="feature">read / write</span>_



<p>Aligned audio aux frames callback.</p>
<p>Available: Since 2.22.0
Description: In this callback, you can receive the audio aux frames which aligned with accompany. Developers can record locally.
When to trigger: This callback function will not be triggered until <code>enableAlignedAudioAuxData</code> is called to turn on the function and <code>startpublishingstream</code> or <code>startrecordingcaptureddata</code> is called.
Restrictions: To obtain audio aux data of the media player from this callback, developers need to call <code>enableAux</code> and <code>start</code> of MediaPlayer.
Caution: This callback is a high-frequency callback, please do not perform time-consuming operations in this callback, and the data in this callback cannot be modified.</p>
<ul>
<li><code>data</code> Audio data in PCM format.</li>
<li><code>param</code> Parameters of the audio frame.</li>
</ul>



## Implementation

```dart
static void Function(Uint8List data, ZegoAudioFrameParam param)?
    onAlignedAudioAuxData;
```







