


# onMediaPlayerFrequencySpectrumUpdate property







(void Function([ZegoMediaPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, List&lt;double> spectrumList)?) onMediaPlayerFrequencySpectrumUpdate
  
_<span class="feature">read / write</span>_



<p>The callback of frequency spectrum update.</p>
<p>Available since: 2.15.0
Description: The callback of frequency spectrum update.
Trigger: The callback frequency is specified by <code>EnableFrequencySpectrumMonitor</code>.
Caution: The callback does not actually take effect until call <code>setEventHandler</code> to set.
Related APIs: To monitor this callback, you need to enable it through <code>EnableFrequencySpectrumMonitor</code>.</p>
<ul>
<li><code>mediaPlayer</code> Callback player object.</li>
<li><code>spectrumList</code> Locally captured frequency spectrum value list. Spectrum value range is <code>0-2^30</code>.</li>
</ul>



## Implementation

```dart
static void Function(ZegoMediaPlayer mediaPlayer, List<double> spectrumList)?
    onMediaPlayerFrequencySpectrumUpdate;
```







