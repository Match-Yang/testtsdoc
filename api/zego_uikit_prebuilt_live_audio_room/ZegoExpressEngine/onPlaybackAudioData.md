


# onPlaybackAudioData property







(void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)?) onPlaybackAudioData
  
_<span class="feature">read / write</span>_



<p>The callback for obtaining the audio data of all the streams playback by SDK.</p>
<p>Available: Since 1.1.0
Description: This function will callback all the mixed audio data to be playback. This callback can be used for that you needs to fetch all the mixed audio data to be playback to proccess.
When to trigger: On the premise of calling <code>setAudioDataHandler</code> to set the listener callback, after calling <code>startAudioDataObserver</code> to set the mask 0b10 that means 1 &lt;&lt; 1, this callback will be triggered only when it is in the SDK inner audio and video engine started(called the <code>startPreivew</code> or <code>startPlayingStream</code> or <code>startPublishingStream</code>).
Restrictions: When playing copyrighted music, this callback will be disabled by default. If necessary, please contact ZEGO technical support.
Caution: This callback is a high-frequency callback, please do not perform time-consuming operations in this callback. When the engine is started in the non-playing stream state or the media player is not used to play the media file, the audio data to be called back is muted audio data.</p>
<ul>
<li><code>data</code> Audio data in PCM format.</li>
<li><code>dataLength</code> Length of the data.</li>
<li><code>param</code> Parameters of the audio frame.</li>
</ul>



## Implementation

```dart
static void Function(
        Uint8List data, int dataLength, ZegoAudioFrameParam param)?
    onPlaybackAudioData;
```







