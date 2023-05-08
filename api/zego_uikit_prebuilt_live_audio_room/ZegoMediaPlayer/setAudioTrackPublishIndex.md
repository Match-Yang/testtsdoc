


# setAudioTrackPublishIndex method








Future&lt;void> setAudioTrackPublishIndex
(int index)





<p>Set the audio track for the media file to be publish.</p>
<p>Available since: 3.1.0
Description: Set the audio track for the media file to be publish.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Related APIs: The number of audio tracks can be obtained through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getAudioTrackCount.md">getAudioTrackCount</a> function.
Caution: This call takes effect only after multitrack mode is enabled by calling the interface <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setAudioTrackMode.md">setAudioTrackMode</a>.</p>
<ul>
<li><code>index</code> Audio track index, the number of audio tracks can be obtained through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getAudioTrackCount.md">getAudioTrackCount</a> function.</li>
</ul>



## Implementation

```dart
Future<void> setAudioTrackPublishIndex(int index);
```







