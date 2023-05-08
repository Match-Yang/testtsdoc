


# onRemoteMicStateUpdate property







(void Function(String streamID, [ZegoRemoteDeviceState](../../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) state)?) onRemoteMicStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the state of the remote microphone changes.</p>
<p>Available since: 1.1.0
Description: The callback triggered when the state of the remote microphone changes.
Use cases: Developers of 1v1 education scenarios or education small class scenarios and similar scenarios can use this callback notification to determine whether the microphone device of the remote publishing stream device is working normally, and preliminary understand the cause of the device problem according to the corresponding state.
Trigger: When the state of the remote microphone device is changed, such as switching a microphone, etc., by listening to the callback, it is possible to obtain an event related to the remote microphone, which can be used to prompt the user that the audio may be abnormal.
Caution: This callback will not be called back when the remote stream is play from the CDN, or when custom audio acquisition is used at the peer (But the stream is not published to the ZEGO RTC server.).</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>state</code> Remote microphone status.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, ZegoRemoteDeviceState state)?
    onRemoteMicStateUpdate;
```







