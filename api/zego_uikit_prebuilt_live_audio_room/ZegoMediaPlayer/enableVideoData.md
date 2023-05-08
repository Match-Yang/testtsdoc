


# enableVideoData method








Future&lt;void> enableVideoData
(bool enable, [ZegoVideoFrameFormat](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoFrameFormat.md) format)





<p>Whether to video data playback.</p>
<p>Available since: 2.1.0
Description: Whether to throw out the video data of the media resource file played by the media player.
When to call: After the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md">ZegoMediaPlayer</a> instance created.
Restrictions: None.
Caution: When you no longer need to get the video frame data, please call this function again to clear the handler to stop the video frame data callback.</p>
<ul>
<li><code>enable</code> Video data playback flag. The default is false.</li>
<li><code>format</code> Video frame format for video data</li>
</ul>



## Implementation

```dart
Future<void> enableVideoData(bool enable, ZegoVideoFrameFormat format);
```







