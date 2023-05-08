


# onMediaPlayerStateUpdate property







(void Function([ZegoMediaPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, [ZegoMediaPlayerState](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerState.md) state, int errorCode)?) onMediaPlayerStateUpdate
  
_<span class="feature">read / write</span>_



<p>MediaPlayer playback status callback.</p>
<p>Available since: 1.3.4
Description: MediaPlayer playback status callback.
Trigger: The callback triggered when the state of the media player changes.
Restrictions: None.</p>
<ul>
<li><code>mediaPlayer</code> Callback player object.</li>
<li><code>state</code> Media player status.</li>
<li><code>errorCode</code> Error code, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
</ul>



## Implementation

```dart
static void Function(ZegoMediaPlayer mediaPlayer, ZegoMediaPlayerState state,
    int errorCode)? onMediaPlayerStateUpdate;
```







