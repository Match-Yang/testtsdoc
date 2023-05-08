


# onMediaPlayerPlayingProgress property







(void Function([ZegoMediaPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, int millisecond)?) onMediaPlayerPlayingProgress
  
_<span class="feature">read / write</span>_



<p>The callback to report the current playback progress of the media player.</p>
<p>Available since: 1.3.4
Description: The callback triggered when the network status of the media player changes. Set the callback interval by calling <code>setProgressInterval</code>. When the callback interval is set to 0, the callback is stopped. The default callback interval is 1 second.
Trigger: When the media player is playing network resources, this callback will be triggered when the status change of the cached data.
Restrictions: None.
Related APIs: <code>setProgressInterval</code>.</p>
<ul>
<li><code>mediaPlayer</code> Callback player object.</li>
<li><code>millisecond</code> Progress in milliseconds.</li>
</ul>



## Implementation

```dart
static void Function(ZegoMediaPlayer mediaPlayer, int millisecond)?
    onMediaPlayerPlayingProgress;
```







