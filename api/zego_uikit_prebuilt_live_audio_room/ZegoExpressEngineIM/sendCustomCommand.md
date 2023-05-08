


# sendCustomCommand method








Future&lt;[ZegoIMSendCustomCommandResult](../../zego_uikit_prebuilt_live_audio_room/ZegoIMSendCustomCommandResult-class.md)> sendCustomCommand
(String roomID, String command, List&lt;[ZegoUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUser-class.md)> toUserList)





<p>Sends a Custom Command to the specified users in the same room.</p>
<p>Available since: 1.2.1
Description: After calling this function, users in the same room who have entered the room can receive the message, the message is unreliable.
Use cases: Generally used in scenarios where there is a large number of messages sent and received in the room and the reliability of the messages is not required, such as live barrage.
When to call: After calling <code>loginRoom</code> to log in to the room.
Restrictions: Generally used when the number of people in the live room does not exceed 500.The frequency of sending barrage messages in the same room cannot be higher than 20 messages/s. For restrictions on the use of this function, please contact ZEGO technical support.
Related callbacks: The room custom command can be received through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvCustomCommand.md">onIMRecvCustomCommand</a>.
Related APIs: Broadcast messages can be sent through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendBroadcastMessage.md">sendBroadcastMessage</a> function, and barrage messages can be sent through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendBarrageMessage.md">sendBarrageMessage</a> function.
Privacy reminder: Please do not fill in sensitive user information in this interface, including but not limited to mobile phone number, ID number, passport number, real name, etc.</p>
<ul>
<li><code>roomID</code> Room ID, a string of up to 128 bytes in length.
Caution:
<ol>
<li>room ID is defined by yourself.</li>
<li>Only support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.</li>
<li>If you need to communicate with the Web SDK, please do not use '%'.</li>
</ol>
</li>
<li><code>command</code> Custom command content. Required: Yes. Value range: The maximum length is 1024 bytes. Caution: To protect privacy, please do not fill in sensitive user information in this interface, including but not limited to mobile phone number, ID number, passport number, real name, etc.</li>
<li><code>toUserList</code> List of recipients of signaling. Required: Yes. Value range: user list or <code>null</code>. Caution: When it is <code>null</code>, the SDK will send custom signaling back to all users in the room</li>
<li>Returns Send command result callback.</li>
</ul>



## Implementation

```dart
Future<ZegoIMSendCustomCommandResult> sendCustomCommand(
    String roomID, String command, List<ZegoUser> toUserList) async {
  return await ZegoExpressImpl.instance
      .sendCustomCommand(roomID, command, toUserList);
}
```







