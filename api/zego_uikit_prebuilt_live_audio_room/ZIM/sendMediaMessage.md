


# sendMediaMessage method








Future&lt;[ZIMMessageSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)> sendMediaMessage
([ZIMMediaMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMediaMessage-class.md) message, String toConversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageSendConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config, [ZIMMediaMessageSendNotification](../../zego_uikit_prebuilt_live_audio_room/ZIMMediaMessageSendNotification-class.md)? notification)





<p>Send media messages.
Supported versions: 2.1.5 and above.</p>
<p>Detailed description: This method can be used to send messages in single chat, room and group chat.</p>
<p>Business scenario: When you need to send media to the target user, target message room, and target group chat after logging in, send it through this interface.</p>
<p>Call timing/Notification timing: It can be called after login.</p>
<p>Usage limit: no more than 10/s, available after login, unavailable after logout.</p>
<p>Impact: <code>ZIMEventHandler.onReceivePeerMessage</code>、<code>ZIMEventHandler.onReceiveGroupMessage</code> sessions and session-scoped <code>ZIMEventHandler.onReceiveGroupMessage</code> sessions did not fire message receiver's <code>ZIMEventHandler.onConversationChanged</code> fires <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code> objection.</p>
<p>Note: Have a breaking change in version 2.4.0 of this interface,see changelog for details.Only required if you need to use the threaded update feature when pushing configuration. Push notifications are not supported, nor are <code>ZIMEventHandler.onConversationChanged</code> and <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code> supported if media messages are broadcast to the world.</p>
<p>Related: <code>ZIMMessageSentResult</code>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIMMediaUploadingProgress.md">ZIMMediaUploadingProgress</a>, <code>ZIMEventHandler.onReceivePeerMessage</code>, <code>ZIMEventHandler.onReceiveRoomMessage</code>, <code>ZIMEventHandler.onReceiveGroupMessage</code>, <code>ZIMEventHandler.onConversationChanged</code>, <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code>.</p>
<p>Related interfaces: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryHistoryMessage.md">queryHistoryMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteAllMessage.md">deleteAllMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteMessages.md">deleteMessages</a></p>
<p><code>message</code> The message to be sent.
<code>toConversationID</code> The ID of the conversation which will receive the message.
<code>conversationType</code> The type of the conversation which will receive the message.
<code>config</code> Related configuration for sending single chat messages.
<code>notification</code> Relevant notifications when sending media messages, including upload progress, etc.</p>



## Implementation

```dart
Future<ZIMMessageSentResult> sendMediaMessage(
    ZIMMediaMessage message,
    String toConversationID,
    ZIMConversationType conversationType,
    ZIMMessageSendConfig config,
    ZIMMediaMessageSendNotification? notification);
```







