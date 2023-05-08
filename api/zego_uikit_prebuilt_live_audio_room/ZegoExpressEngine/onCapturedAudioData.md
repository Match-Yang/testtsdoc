


# onCapturedAudioData property







(void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)?) onCapturedAudioData
  
_<span class="feature">read / write</span>_



<p>The callback for obtaining the audio data captured by the local microphone.</p>
<p>Available: Since 1.1.0
Description: In non-custom audio capture mode, the SDK capture the microphone's sound, but the developer may also need to get a copy of the audio data captured by the SDK is available through this callback.
When to trigger: On the premise of calling <code>setAudioDataHandler</code> to set the listener callback, after calling <code>startAudioDataObserver</code> to set the mask 0b01 that means 1 &lt;&lt; 0, this callback will be triggered only when it is in the publishing stream state.
Restrictions: None.
Caution: This callback is a high-frequency callback, please do not perform time-consuming operations in this callback.</p>
<ul>
<li><code>data</code> Audio data in PCM format.</li>
<li><code>dataLength</code> Length of the data.</li>
<li><code>param</code> Parameters of the audio frame.</li>
</ul>



## Implementation

```dart
static void Function(
        Uint8List data, int dataLength, ZegoAudioFrameParam param)?
    onCapturedAudioData;
```







