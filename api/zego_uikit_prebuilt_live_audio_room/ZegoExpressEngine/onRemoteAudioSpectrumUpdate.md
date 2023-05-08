


# onRemoteAudioSpectrumUpdate property







(void Function(Map&lt;String, List&lt;double>> audioSpectrums)?) onRemoteAudioSpectrumUpdate
  
_<span class="feature">read / write</span>_



<p>The remote playing streams audio spectrum callback.</p>
<p>Available since: 1.1.0
Description: The remote playing streams audio spectrum callback.
Trigger: After you start the audio spectrum monitor by calling <code>startAudioSpectrumMonitor</code>, you are in the state of playing the stream <code>startPlayingStream</code>.
Caution: The callback notification period is the parameter value set when the <code>startAudioSpectrumMonitor</code> is called.
Related APIs: Start audio spectrum monitoring via <code>startAudioSpectrumMonitor</code>. Monitoring local played audio spectrum by callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedAudioSpectrumUpdate.md">onCapturedAudioSpectrumUpdate</a>.</p>
<ul>
<li><code>audioSpectrums</code> Remote audio spectrum hash map, key is the streamID, value is the audio spectrum list of the corresponding streamID. Spectrum value range is <code>0-2^30</code></li>
</ul>



## Implementation

```dart
static void Function(Map<String, List<double>> audioSpectrums)?
    onRemoteAudioSpectrumUpdate;
```







