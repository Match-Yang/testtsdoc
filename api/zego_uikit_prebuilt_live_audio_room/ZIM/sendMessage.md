


# sendMessage method








Future&lt;[ZIMMessageSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)> sendMessage
([ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String toConversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageSendConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config, [[ZIMMessageSendNotification](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendNotification-class.md)? notification])





<p>Supported versions: 2.4.0 and above.</p>
<p>Detailed description: This method can be used to send messages in single chat, room and group chat.</p>
<p>Business scenario: When you need to send message to the target user, target message room, and target group chat after logging in, send it through this interface.</p>
<p>Call timing: It can be called after login.</p>
<p>Usage limit: no more than 10/s, available after login, unavailable after logout.</p>
<p>Related callback: <code>ZIMMessageSentResult</code>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendNotification-class.md">ZIMMessageSendNotification</a>, <code>ZIMEventHandler.onReceivePeerMessage</code>, <code>ZIMEventHandler.onReceiveRoomMessage</code>, <code>ZIMEventHandler.onReceiveGroupMessage</code>, <code>ZIMEventHandler.onConversationChanged</code>, <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code>.</p>
<p>Related interfaces: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryHistoryMessage.md">queryHistoryMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteAllMessage.md">deleteAllMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteMessages.md">deleteMessages</a>,<a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendMediaMessage.md">sendMediaMessage</a>.</p>



## Implementation

```dart
Future<ZIMMessageSentResult> sendMessage(
    ZIMMessage message,
    String toConversationID,
    ZIMConversationType conversationType,
    ZIMMessageSendConfig config,
    [ZIMMessageSendNotification? notification]);
```







