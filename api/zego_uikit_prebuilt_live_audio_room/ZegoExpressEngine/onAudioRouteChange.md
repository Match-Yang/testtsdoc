


# onAudioRouteChange property







(void Function([ZegoAudioRoute](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioRoute.md) audioRoute)?) onAudioRouteChange
  
_<span class="feature">read / write</span>_



<p>Callback for device's audio route changed.</p>
<p>Available since: 1.20.0
Description: Callback for device's audio route changed.
Trigger: This callback will be called when there are changes in audio routing such as earphone plugging, speaker and receiver switching, etc.
Platform differences: Only supports iOS and Android.</p>
<ul>
<li><code>audioRoute</code> Current audio route.</li>
</ul>



## Implementation

```dart
static void Function(ZegoAudioRoute audioRoute)? onAudioRouteChange;
```







