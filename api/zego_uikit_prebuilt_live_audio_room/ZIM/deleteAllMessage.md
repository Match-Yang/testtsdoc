


# deleteAllMessage method








Future&lt;[ZIMMessageDeletedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageDeletedResult-class.md)> deleteAllMessage
(String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageDeleteConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageDeleteConfig-class.md) config)





<p>Supported versions: 2.1.5 and above.</p>
<p>Detail description: When you need to delete all messages under the target session, call this method.</p>
<p>Business scenario: If you want to implement a group setting page to clear the chat information under the current session, you can call this interface.</p>
<p>Call timing/Notify timing: The target session exists and the user is a member of this session.</p>
<p>Restrictions: Effective after login, invalid after logout.</p>
<p>Note: The impact of deleting messages is limited to this account, and messages from other accounts will not be deleted.</p>
<p>Scope of influence: The <code>ZIMEventHandler.onConversationChanged</code> callback is triggered, and if there are unread messages, the <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code> callback is triggered.</p>
<p>Related callback: <code>ZIMMessageDeletedResult</code>.</p>
<p><code>conversationID</code> The session ID of the message to be deleted.
<code>conversationType</code>  conversation type.
<code>config</code> delete session configuration.</p>



## Implementation

```dart
Future<ZIMMessageDeletedResult> deleteAllMessage(String conversationID,
    ZIMConversationType conversationType, ZIMMessageDeleteConfig config);
```







