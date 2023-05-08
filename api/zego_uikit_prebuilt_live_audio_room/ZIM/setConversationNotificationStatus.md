


# setConversationNotificationStatus method








Future&lt;[ZIMConversationNotificationStatusSetResult](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationNotificationStatusSetResult-class.md)> setConversationNotificationStatus
([ZIMConversationNotificationStatus](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationNotificationStatus.md) status, String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType)





<p>Available since: 2.1.5 and above.</p>
<p>Description: This method enables DND by selecting whether the unread of the target session is updated when a message is received.</p>
<p>Use cases: If the user selects MESSAGE DO not Disturb (DND), the user can call the corresponding method.</p>
<p>Default value: Message DND is disabled by default.</p>
<p>When to call /Trigger: If the target session exists after login, invoke this interface if you want to enable the DND status of the target session.</p>
<p>Restrictions:  Valid after login, invalid after logout.</p>
<p>Impacts on other APIs: After the DND state is enabled, receiving messages is not triggered <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code>.</p>
<p>Related callbacks: <code>ZIMConversationNotificationStatusSetResult</code>.</p>
<p>Related APIs: <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code>.</p>
<p><code>status</code> the session notification state.
<code>conversationID</code>  conversationID.
<code>conversationType</code> conversation type.</p>



## Implementation

```dart
Future<ZIMConversationNotificationStatusSetResult>
    setConversationNotificationStatus(
        ZIMConversationNotificationStatus status,
        String conversationID,
        ZIMConversationType conversationType);
```







