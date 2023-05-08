


# onRangeAudioMicrophoneStateUpdate property







(void Function([ZegoRangeAudio](../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio-class.md) rangeAudio, [ZegoRangeAudioMicrophoneState](../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudioMicrophoneState.md) state, int errorCode)?) onRangeAudioMicrophoneStateUpdate
  
_<span class="feature">read / write</span>_



<p>Range audio microphone state callback.</p>
<p>Available since: 2.11.0
Description: The status change notification of the microphone, starting to send audio is an asynchronous process, and the state switching in the middle is called back through this function.
When to Trigger: After the <code>enableMicrophone</code> function.
Caution: It must be monitored before the <code>enableMicrophone</code> function is called.</p>
<ul>
<li><code>rangeAudio</code> Range audio instance that triggers this callback.</li>
<li><code>state</code> The use state of the range audio.</li>
<li><code>errorCode</code> Error code, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
</ul>



## Implementation

```dart
static void Function(
    ZegoRangeAudio rangeAudio,
    ZegoRangeAudioMicrophoneState state,
    int errorCode)? onRangeAudioMicrophoneStateUpdate;
```







