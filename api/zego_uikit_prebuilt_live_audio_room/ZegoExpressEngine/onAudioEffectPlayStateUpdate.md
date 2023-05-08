


# onAudioEffectPlayStateUpdate property







(void Function([ZegoAudioEffectPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer-class.md) audioEffectPlayer, int audioEffectID, [ZegoAudioEffectPlayState](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayState.md) state, int errorCode)?) onAudioEffectPlayStateUpdate
  
_<span class="feature">read / write</span>_



<p>Audio effect playback state callback.</p>
<p>Available since: 1.16.0
Description: This callback is triggered when the playback state of a audio effect of the audio effect player changes.
Trigger: This callback is triggered when the playback status of the audio effect changes.
Restrictions: None.</p>
<ul>
<li><code>audioEffectPlayer</code> Audio effect player instance that triggers this callback.</li>
<li><code>audioEffectID</code> The ID of the audio effect resource that triggered this callback.</li>
<li><code>state</code> The playback state of the audio effect.</li>
<li><code>errorCode</code> Error code, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
</ul>



## Implementation

```dart
static void Function(
    ZegoAudioEffectPlayer audioEffectPlayer,
    int audioEffectID,
    ZegoAudioEffectPlayState state,
    int errorCode)? onAudioEffectPlayStateUpdate;
```







