


# onIMRecvBroadcastMessage property







(void Function(String roomID, List&lt;[ZegoBroadcastMessageInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoBroadcastMessageInfo-class.md)> messageList)?) onIMRecvBroadcastMessage
  
_<span class="feature">read / write</span>_



<p>The callback triggered when Broadcast Messages are received.</p>
<p>Available since: 1.2.1
Description: This callback is used to receive broadcast messages sent by other users in the same room.
Use cases: Generally used when the number of people in the live room does not exceed 500
When to trigger: After calling <code>loginRoom</code> to log in to the room, if a user in the room sends a broadcast message via <code>sendBroadcastMessage</code> function, this callback will be triggered.
Restrictions: None
Caution: The broadcast message sent by the user will not be notified through this callback.
Related callbacks: You can receive room barrage messages through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBarrageMessage.md">onIMRecvBarrageMessage</a>, and you can receive room custom signaling through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvCustomCommand.md">onIMRecvCustomCommand</a>.</p>
<ul>
<li><code>roomID</code> Room ID. Value range: The maximum length is 128 bytes.</li>
<li><code>messageList</code> List of received messages. Value range: Up to 50 messages can be received each time.</li>
</ul>



## Implementation

```dart
static void Function(
        String roomID, List<ZegoBroadcastMessageInfo> messageList)?
    onIMRecvBroadcastMessage;
```







