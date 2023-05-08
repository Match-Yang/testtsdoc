


# deleteMessages method








Future&lt;[ZIMMessageDeletedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageDeletedResult-class.md)> deleteMessages
(List&lt;[ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md)> messageList, String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageDeleteConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageDeleteConfig-class.md) config)





<p>Supported versions: 2.1.5 and above.
Detail description: This method implements the function of deleting messages.
Business scenario: The user needs to delete a message. When the user does not need to display a message, this method can be used to delete it.
Call timing/Notification timing: Called when the message needs to be deleted.
Note: The impact of deleting messages is limited to this account.
Restrictions: Effective after login, invalid after logout.
Scope of influence: If the deleted message is the latest message of the session, the <code>ZIMEventHandler..onConversationChanged</code> callback will be triggered, and if the message is unread, the <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code> callback will be triggered.</p>
<p><code>messageList</code> List of deleted messages.
<code>conversationID</code> conversation ID.
<code>conversationType</code> conversation type.
<code>config</code>  Delete the configuration of the message.</p>



## Implementation

```dart
/// Detail description: This method implements the function of deleting messages.

/// Business scenario: The user needs to delete a message. When the user does not need to display a message, this method can be used to delete it.

/// Call timing/Notification timing: Called when the message needs to be deleted.

/// Note: The impact of deleting messages is limited to this account.

/// Restrictions: Effective after login, invalid after logout.

/// Scope of influence: If the deleted message is the latest message of the session, the [ZIMEventHandler..onConversationChanged] callback will be triggered, and if the message is unread, the [ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated] callback will be triggered.
///
/// [messageList] List of deleted messages.
/// [conversationID] conversation ID.
/// [conversationType] conversation type.
/// [config]  Delete the configuration of the message.
Future<ZIMMessageDeletedResult> deleteMessages(
    List<ZIMMessage> messageList,
    String conversationID,
    ZIMConversationType conversationType,
    ZIMMessageDeleteConfig config);
```







