


# setAudioTrackMode method








Future&lt;void> setAudioTrackMode
([ZegoMediaPlayerAudioTrackMode](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerAudioTrackMode.md) mode)





<p>Set the audio track mode of the player.</p>
<p>Available since: 3.1.0
Description: Set the audio track mode of the player.
Use case: Under the real-time chorus (KTV), call the interface enable multi-track mode, call the interface <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setAudioTrackIndex.md">setAudioTrackIndex</a> to specify the original track to play, call interface <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setAudioTrackPublishIndex.md">setAudioTrackPublishIndex</a> specified need publish of accompaniment tracks.
When to call: The call takes effect before <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/start.md">start</a> starts playing
Related APIs: Call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setAudioTrackIndex.md">setAudioTrackIndex</a> to specified the play track of media file and call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setAudioTrackPublishIndex.md">setAudioTrackPublishIndex</a> to specified the publish track of media file.
Caution: When multi-track mode is enabled, the resource consumption of the hardware device is increased.</p>
<ul>
<li><code>mode</code> Audio track mode.</li>
</ul>



## Implementation

```dart
Future<void> setAudioTrackMode(ZegoMediaPlayerAudioTrackMode mode);
```







