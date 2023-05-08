


# deleteConversation method








Future&lt;[ZIMConversationDeletedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationDeletedResult-class.md)> deleteConversation
(String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMConversationDeleteConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationDeleteConfig-class.md) config)





<p>Available since: 2.1.5 and above.</p>
<p>Description: This interface is invoked when a session needs to be deleted. All members in the session can invoke this interface.</p>
<p>Use cases: You can invoke this interface implementation to delete an entire session when it is no longer needed.</p>
<p>When to call /Trigger: his parameter is invoked when a session needs to be deleted and can be invoked after a ZIM instance is created. The call takes effect after login and becomes invalid after logout.</p>
<p><code>conversationID</code> conversationID.
<code>conversationType</code> conversation type.
<code>config</code> delete the session's configuration.</p>



## Implementation

```dart
Future<ZIMConversationDeletedResult> deleteConversation(String conversationID,
    ZIMConversationType conversationType, ZIMConversationDeleteConfig config);
```







