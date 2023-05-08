


# onRemoteSpeakerStateUpdate property







(void Function(String streamID, [ZegoRemoteDeviceState](../../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) state)?) onRemoteSpeakerStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the state of the remote speaker changes.</p>
<p>Available since: 1.1.0
Description: The callback triggered when the state of the remote microphone changes.
Use cases: Developers of 1v1 education scenarios or education small class scenarios and similar scenarios can use this callback notification to determine whether the speaker device of the remote publishing stream device is working normally, and preliminary understand the cause of the device problem according to the corresponding state.
Trigger: When the state of the remote speaker device changes, such as switching the speaker, by monitoring this callback, you can get events related to the remote speaker.
Caution: This callback will not be called back when the remote stream is play from the CDN.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>state</code> Remote speaker status.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, ZegoRemoteDeviceState state)?
    onRemoteSpeakerStateUpdate;
```







