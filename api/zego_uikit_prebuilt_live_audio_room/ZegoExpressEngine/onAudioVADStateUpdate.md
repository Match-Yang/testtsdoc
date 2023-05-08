


# onAudioVADStateUpdate property







(void Function([ZegoAudioVADStableStateMonitorType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVADStableStateMonitorType.md) type, [ZegoAudioVADType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVADType.md) state)?) onAudioVADStateUpdate
  
_<span class="feature">read / write</span>_



<p>Callback for audio VAD  stable state update.</p>
<p>Available since: 2.14.0
Description: Callback for audio VAD  stable state update.
When to trigger: the <code>startAudioVADStableStateMonitor</code> function must be called to start the audio VAD monitor and you must be in a state where it is publishing the audio and video stream or be in <code>startPreview</code> state.
Restrictions: The callback notification period is 3 seconds.
Related APIs: <code>startAudioVADStableStateMonitor</code>, <code>stopAudioVADStableStateMonitor</code>.</p>
<ul>
<li><code>type</code> audio VAD monitor type</li>
<li><code>state</code> VAD result</li>
</ul>



## Implementation

```dart
static void Function(
        ZegoAudioVADStableStateMonitorType type, ZegoAudioVADType state)?
    onAudioVADStateUpdate;
```







