


# onRemoteCameraStateUpdate property







(void Function(String streamID, [ZegoRemoteDeviceState](../../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) state)?) onRemoteCameraStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the state of the remote camera changes.</p>
<p>Available since: 1.1.0
Description: The callback triggered when the state of the remote camera changes.
Use cases: Developers of 1v1 education scenarios or education small class scenarios and similar scenarios can use this callback notification to determine whether the camera device of the remote publishing stream device is working normally, and preliminary understand the cause of the device problem according to the corresponding state.
Trigger: When the state of the remote camera device changes, such as switching the camera, by monitoring this callback, it is possible to obtain an event related to the far-end camera, which can be used to prompt the user that the video may be abnormal.
Caution: This callback will not be called back when the remote stream is play from the CDN, or when custom video acquisition is used at the peer.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>state</code> Remote camera status.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, ZegoRemoteDeviceState state)?
    onRemoteCameraStateUpdate;
```







