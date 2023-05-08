


# onMediaPlayerSoundLevelUpdate property







(void Function([ZegoMediaPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, double soundLevel)?) onMediaPlayerSoundLevelUpdate
  
_<span class="feature">read / write</span>_



<p>The callback of sound level update.</p>
<p>Available since: 2.15.0
Description: The callback of sound level update.
Trigger: The callback frequency is specified by <code>EnableSoundLevelMonitor</code>.
Caution: The callback does not actually take effect until call <code>setEventHandler</code> to set.
Related APIs: To monitor this callback, you need to enable it through <code>EnableSoundLevelMonitor</code>.</p>
<ul>
<li><code>mediaPlayer</code> Callback player object.</li>
<li><code>soundLevel</code> Sound level value, value range: <code>0.0, 100.0</code>.</li>
</ul>



## Implementation

```dart
static void Function(ZegoMediaPlayer mediaPlayer, double soundLevel)?
    onMediaPlayerSoundLevelUpdate;
```







