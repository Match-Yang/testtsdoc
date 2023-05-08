


# onCurrentPitchValueUpdate property







(void Function([ZegoCopyrightedMusic](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic-class.md) copyrightedMusic, String resourceID, int currentDuration, int pitchValue)?) onCurrentPitchValueUpdate
  
_<span class="feature">read / write</span>_



<p>Real-time pitch line callback.</p>
<ul>
<li><code>copyrightedMusic</code> Copyrighted music instance that triggers this callback.</li>
<li><code>resourceID</code> The resource ID of the song or accompaniment that triggered this callback.</li>
<li><code>currentDuration</code> Current playback progress.</li>
<li><code>pitchValue</code> Real-time pitch accuracy or value.</li>
</ul>



## Implementation

```dart
static void Function(ZegoCopyrightedMusic copyrightedMusic, String resourceID,
    int currentDuration, int pitchValue)? onCurrentPitchValueUpdate;
```







