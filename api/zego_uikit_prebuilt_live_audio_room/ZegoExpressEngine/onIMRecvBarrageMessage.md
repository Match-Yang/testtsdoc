


# onIMRecvBarrageMessage property







(void Function(String roomID, List&lt;[ZegoBarrageMessageInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoBarrageMessageInfo-class.md)> messageList)?) onIMRecvBarrageMessage
  
_<span class="feature">read / write</span>_



<p>The callback triggered when Barrage Messages are received.</p>
<p>Available since: 1.5.0
Description: This callback is used to receive barrage messages sent by other users in the same room.
Use cases: Generally used in scenarios where there is a large number of messages sent and received in the room and the reliability of the messages is not required, such as live barrage.
When to trigger: After calling <code>loginRoom</code> to log in to the room, if a user in the room sends a barrage message through the <code>sendBarrageMessage</code> function, this callback will be triggered.
Restrictions: None
Caution: Barrage messages sent by users themselves will not be notified through this callback. When there are a large number of barrage messages in the room, the notification may be delayed, and some barrage messages may be lost.
Related callbacks: Develop can receive room broadcast messages through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBroadcastMessage.md">onIMRecvBroadcastMessage</a>, and can receive room custom signaling through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvCustomCommand.md">onIMRecvCustomCommand</a>.</p>
<ul>
<li><code>roomID</code> Room ID. Value range: The maximum length is 128 bytes.</li>
<li><code>messageList</code> List of received messages. Value range: Up to 50 messages can be received each time.</li>
</ul>



## Implementation

```dart
static void Function(String roomID, List<ZegoBarrageMessageInfo> messageList)?
    onIMRecvBarrageMessage;
```







