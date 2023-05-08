


# onProcessCapturedAudioData property







(void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, double timestamp)?) onProcessCapturedAudioData
  
_<span class="feature">read / write</span>_



<p>Custom audio processing local captured PCM audio frame callback.</p>
<p>Available: Since 2.13.0
Description: In this callback, you can receive the PCM audio frames captured locally after used headphone monitor. Developers can modify the audio frame data, as well as the audio channels and sample rate. The timestamp can be used for data synchronization, such as lyrics, etc. If you need the data after used headphone monitor, please use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onProcessCapturedAudioDataAfterUsedHeadphoneMonitor.md">onProcessCapturedAudioDataAfterUsedHeadphoneMonitor</a> callback.
When to trigger: You need to call <code>enableCustomAudioCaptureProcessing</code> to enable the function first, and call <code>startPreivew</code> or <code>startPublishingStream</code> to trigger this callback function.
Restrictions: None.
Caution: This callback is a high-frequency callback, please do not perform time-consuming operations in this callback.</p>
<ul>
<li><code>data</code> Audio data in PCM format.</li>
<li><code>dataLength</code> Length of the data.</li>
<li><code>param</code> Parameters of the audio frame.</li>
<li><code>timestamp</code> The audio frame timestamp, starting from 0 when capture is started, the unit is milliseconds.</li>
</ul>



## Implementation

```dart
static void Function(Uint8List data, int dataLength,
    ZegoAudioFrameParam param, double timestamp)? onProcessCapturedAudioData;
```







