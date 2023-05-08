


# sendGroupMessage method








Future&lt;[ZIMMessageSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)> sendGroupMessage
([ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String toGroupID, [ZIMMessageSendConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config)





<p>deprecated: This API has been deprecated since 2.4.0, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a> instead.</p>
<p>Supported versions: 2.1.5 and above.
Detail description: This interface is called when a group chat message needs to be sent.
Business scenario: This interface can be used when sending group messages.
Call timing/Notification timing: This interface is called when a group chat message needs to be sent.
Usage limit: 10 times/s, available after login, unavailable after logout.
Note: pushConfig only needs to be filled in when you need to use the offline push function. The properties in ZIMMessage are read-only and do not need to be modified.
Scope of influence: Using this method will trigger the receivePeerMessage callback of the message receiver, and will trigger the onConversationChanged callback of the sender and receiver. If the session where the message is located does not have message DND set, the conversationTotalUnreadMessageCountUpdated callback will be triggered.
Related callbacks: <code>ZIMMessageSentResult</code>, <code>ZIMEventHandler.onReceiveGroupMessage</code>, <code>ZIMEventHandler.onConversationChanged</code>, <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code>.
Related interfaces: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryHistoryMessage.md">queryHistoryMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteMessages.md">deleteMessages</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteAllMessage.md">deleteAllMessage</a></p>
<p><code>message</code> The message to be sent.
<code>toGroupID</code> The ID of the user who will receive the message.
<code>config</code> Related configuration for sending single chat messages.</p>



## Implementation

```dart
/// Detail description: This interface is called when a group chat message needs to be sent.

/// Business scenario: This interface can be used when sending group messages.

/// Call timing/Notification timing: This interface is called when a group chat message needs to be sent.

/// Usage limit: 10 times/s, available after login, unavailable after logout.

/// Note: pushConfig only needs to be filled in when you need to use the offline push function. The properties in ZIMMessage are read-only and do not need to be modified.

/// Scope of influence: Using this method will trigger the receivePeerMessage callback of the message receiver, and will trigger the onConversationChanged callback of the sender and receiver. If the session where the message is located does not have message DND set, the conversationTotalUnreadMessageCountUpdated callback will be triggered.

/// Related callbacks: [ZIMMessageSentResult], [ZIMEventHandler.onReceiveGroupMessage], [ZIMEventHandler.onConversationChanged], [ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated].

/// Related interfaces: [queryHistoryMessage], [deleteMessages], [deleteAllMessage]
///
/// [message] The message to be sent.
/// [toGroupID] The ID of the user who will receive the message.
/// [config] Related configuration for sending single chat messages.
Future<ZIMMessageSentResult> sendGroupMessage(
    ZIMMessage message, String toGroupID, ZIMMessageSendConfig config);
```







