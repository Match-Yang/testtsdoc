


# insertMessageToLocalDB method








Future&lt;[ZIMMessageInsertedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageInsertedResult-class.md)> insertMessageToLocalDB
([ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, String senderUserID)





<p>Supported Versions: 2.4.0 and above.</p>
<p>Detail description: This method can insert a message directly to the local DB on the client side.</p>
<p>Business scenario: The developer can combine the system message type, and convert the callback notification (for example, invite someone into the group, remove someone from the group, etc.) to the system message type on the client side and insert it into the local DB to achieve the effect of the system prompt .</p>
<p>Call timing/Notification timing: It can be called after login.</p>
<p>Usage Restrictions: Currently, only chat and group messages can be inserted. Room messages cannot be inserted.</p>
<p>Related callback: <code>ZIMMessageInsertedResult</code>.</p>
<p>Related interfaces: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryHistoryMessage.md">queryHistoryMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteAllMessage.md">deleteAllMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteMessages.md">deleteMessages</a>.</p>



## Implementation

```dart
Future<ZIMMessageInsertedResult> insertMessageToLocalDB(
    ZIMMessage message,
    String conversationID,
    ZIMConversationType conversationType,
    String senderUserID);
```







