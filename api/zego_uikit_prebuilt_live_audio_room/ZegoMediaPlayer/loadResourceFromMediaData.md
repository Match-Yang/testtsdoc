


# loadResourceFromMediaData method








Future&lt;[ZegoMediaPlayerLoadResourceResult](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerLoadResourceResult-class.md)> loadResourceFromMediaData
(Uint8List mediaData, int startPosition)





<p>Load media resource.</p>
<p>Available: since 2.10.0
Description: Load binary audio data.
Use case: Developers do not want to cache the audio data locally, and directly transfer the audio binary data to the media player, directly load and play the audio.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Related APIs: Resources can be loaded through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResource.md">loadResource</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResourceWithPosition.md">loadResourceWithPosition</a> function.
Caution: When <code>startPosition</code> exceeds the total playing time, it will start playing from the beginning.</p>
<ul>
<li><code>mediaData</code> Binary audio data.</li>
<li><code>startPosition</code> Position of starting playback, in milliseconds.</li>
<li>Returns Callback result of loading media resource.</li>
</ul>



## Implementation

```dart
Future<ZegoMediaPlayerLoadResourceResult> loadResourceFromMediaData(
    Uint8List mediaData, int startPosition);
```







