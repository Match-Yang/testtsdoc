


# clearConversationUnreadMessageCount method








Future&lt;[ZIMConversationUnreadMessageCountClearedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationUnreadMessageCountClearedResult-class.md)> clearConversationUnreadMessageCount
(String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType)





<p>Available since: 2.1.5 and above.</p>
<p>Description: Used to clear unread for the current user target session.</p>
<p>Use cases: This interface is called when a chat page is entered from a session and the original message readings of the session need to be cleared.</p>
<p>When to call /Trigger: Called when a target needs to be cleared without readings.</p>
<p>Restrictions: Valid after login, invalid after logout.</p>
<p>Impacts on other APIs: Calling this method will trigger a total readings not updated callback <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code>, would trigger a session to update callbacks <code>ZIMEventHandler.onConversationChanged</code>.</p>
<p>Related callbacks:<code>ZIMConversationUnreadMessageCountClearedResult</code>.</p>
<p>Related APIs:<code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code>、<code>ZIMEventHandler.onConversationChanged</code>.</p>
<p><code>conversationID</code> conversationID.
<code>conversationType</code> conversation type.</p>



## Implementation

```dart
Future<ZIMConversationUnreadMessageCountClearedResult>
    clearConversationUnreadMessageCount(
        String conversationID, ZIMConversationType conversationType);
```







