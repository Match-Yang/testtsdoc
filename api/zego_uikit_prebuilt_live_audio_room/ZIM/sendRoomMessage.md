


# sendRoomMessage method








Future&lt;[ZIMMessageSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)> sendRoomMessage
([ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String toRoomID, [ZIMMessageSendConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config)





<p>deprecated: This API has been deprecated since 2.4.0, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a> instead.</p>
<p>Send room messages.</p>
<p>Available since: 2.1.5 or above</p>
<p>Description: When this function is called, the message will be sent in the room. At the same time, the <code>ZIMMessageSentResult</code> callback will be received, which can be used to determine whether the message was sent successfully.</p>
<p>Use Cases: This feature is required for scenarios where multiple people in the room are chatting.</p>
<p><code>message</code> The message to be sent.
<code>toRoomID</code> The ID of the room which will receive the message.
<code>config</code> Related configuration for sending room messages.</p>



## Implementation

```dart
Future<ZIMMessageSentResult> sendRoomMessage(
    ZIMMessage message, String toRoomID, ZIMMessageSendConfig config);
```







