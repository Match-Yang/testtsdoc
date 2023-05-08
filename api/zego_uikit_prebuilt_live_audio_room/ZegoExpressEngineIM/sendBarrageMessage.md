


# sendBarrageMessage method








Future&lt;[ZegoIMSendBarrageMessageResult](../../zego_uikit_prebuilt_live_audio_room/ZegoIMSendBarrageMessageResult-class.md)> sendBarrageMessage
(String roomID, String message)





<p>Sends a Barrage Message (bullet screen) to all users in the same room, without guaranteeing the delivery.</p>
<p>Available since: 1.5.0
Description: Send a barrage message to the room, users who have logged in to the same room can receive the message, the message is unreliable.
Use cases: Generally used in scenarios where there is a large number of messages sent and received in the room and the reliability of the messages is not required, such as live barrage.
When to call: After calling <code>loginRoom</code> to log in to the room.
Restrictions: The frequency of sending barrage messages in the same room cannot be higher than 20 messages/s. For restrictions on the use of this function, please contact ZEGO technical support.
Related callbacks: The room barrage message can be received through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBarrageMessage.md">onIMRecvBarrageMessage</a>.
Related APIs: Broadcast messages can be sent through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendBroadcastMessage.md">sendBroadcastMessage</a> function, and custom command can be sent through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendCustomCommand.md">sendCustomCommand</a> function.</p>
<ul>
<li><code>roomID</code> Room ID, a string of up to 128 bytes in length.
Caution:
<ol>
<li>room ID is defined by yourself.</li>
<li>Only support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.</li>
<li>If you need to communicate with the Web SDK, please do not use '%'.</li>
</ol>
</li>
<li><code>message</code> The content of the message. Required: Yes. Value range: The length does not exceed 1024 bytes.</li>
<li>Returns Send barrage message result callback.</li>
</ul>



## Implementation

```dart
Future<ZegoIMSendBarrageMessageResult> sendBarrageMessage(
    String roomID, String message) async {
  return await ZegoExpressImpl.instance.sendBarrageMessage(roomID, message);
}
```







