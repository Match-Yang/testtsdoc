


# onCapturedAudioSpectrumUpdate property







(void Function(List&lt;double> audioSpectrum)?) onCapturedAudioSpectrumUpdate
  
_<span class="feature">read / write</span>_



<p>The local captured audio spectrum callback.</p>
<p>Available since: 1.1.0
Description: The local captured audio spectrum callback.
Trigger: After you start the audio spectrum monitor by calling <code>startAudioSpectrumMonitor</code>.
Caution: The callback notification period is the parameter value set when the <code>startAudioSpectrumMonitor</code> is called. The callback value is the default value of 0 When you have not called the interface <code>startPublishingStream</code> and <code>startPreview</code>.
Related APIs: Start audio spectrum monitoring via <code>startAudioSpectrumMonitor</code>. Monitoring remote played audio spectrum by callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteAudioSpectrumUpdate.md">onRemoteAudioSpectrumUpdate</a></p>
<ul>
<li><code>audioSpectrum</code> Locally captured audio spectrum value list. Spectrum value range is <code>0-2^30</code>.</li>
</ul>



## Implementation

```dart
static void Function(List<double> audioSpectrum)?
    onCapturedAudioSpectrumUpdate;
```







