


# sendBroadcastMessage method








Future&lt;[ZegoIMSendBroadcastMessageResult](../../zego_uikit_prebuilt_live_audio_room/ZegoIMSendBroadcastMessageResult-class.md)> sendBroadcastMessage
(String roomID, String message)





<p>Sends a Broadcast Message.</p>
<p>Available since: 1.2.1
Description: Send a broadcast message to the room, users who have entered the same room can receive the message, and the message is reliable.
Use cases: Generally used when the number of people in the live room does not exceed 500.
When to call: After calling <code>loginRoom</code> to log in to the room.
Restrictions: It is not supported when the number of people online in the room exceeds 500. If you need to increase the limit, please contact ZEGO technical support to apply for evaluation. The frequency of sending broadcast messages in the same room cannot be higher than 10 messages/s. The maximum QPS for a single user calling this interface from the client side is 2. For restrictions on the use of this function, please contact ZEGO technical support.
Related callbacks: The room broadcast message can be received through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBroadcastMessage.md">onIMRecvBroadcastMessage</a>.
Related APIs: Barrage messages can be sent through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendBarrageMessage.md">sendBarrageMessage</a> function, and custom command can be sent through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendCustomCommand.md">sendCustomCommand</a> function.</p>
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
<li>Returns Send broadcast message result callback</li>
</ul>



## Implementation

```dart
Future<ZegoIMSendBroadcastMessageResult> sendBroadcastMessage(
    String roomID, String message) async {
  return await ZegoExpressImpl.instance.sendBroadcastMessage(roomID, message);
}
```







