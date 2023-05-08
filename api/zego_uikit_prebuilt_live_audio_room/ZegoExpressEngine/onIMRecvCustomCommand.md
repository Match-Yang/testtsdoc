


# onIMRecvCustomCommand property







(void Function(String roomID, [ZegoUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUser-class.md) fromUser, String command)?) onIMRecvCustomCommand
  
_<span class="feature">read / write</span>_



<p>The callback triggered when a Custom Command is received.</p>
<p>Available since: 1.2.1
Description: This callback is used to receive custom command sent by other users in the same room.
Use cases: Generally used when the number of people in the live room does not exceed 500
When to trigger: After calling <code>loginRoom</code> to log in to the room, if other users in the room send custom signaling to the developer through the <code>sendCustomCommand</code> function, this callback will be triggered.
Restrictions: None
Caution: The custom command sent by the user himself will not be notified through this callback.
Related callbacks: You can receive room broadcast messages through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBroadcastMessage.md">onIMRecvBroadcastMessage</a>, and you can receive room barrage message through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBarrageMessage.md">onIMRecvBarrageMessage</a>.</p>
<ul>
<li><code>roomID</code> Room ID. Value range: The maximum length is 128 bytes.</li>
<li><code>fromUser</code> Sender of the command.</li>
<li><code>command</code> Command content received.Value range: The maximum length is 1024 bytes.</li>
</ul>



## Implementation

```dart
static void Function(String roomID, ZegoUser fromUser, String command)?
    onIMRecvCustomCommand;
```







