


# onMediaPlayerRecvSEI property







(void Function([ZegoMediaPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, Uint8List data)?) onMediaPlayerRecvSEI
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the media player got media side info.</p>
<p>Available since: 2.2.0
Description: The callback triggered when the media player got media side info.
Trigger: When the media player starts playing media files, the callback is triggered if the SEI is resolved to the media file.
Caution: The callback does not actually take effect until call <code>setEventHandler</code> to set.</p>
<ul>
<li><code>mediaPlayer</code> Callback player object.</li>
<li><code>data</code> SEI content.</li>
</ul>



## Implementation

```dart
static void Function(ZegoMediaPlayer mediaPlayer, Uint8List data)?
    onMediaPlayerRecvSEI;
```







