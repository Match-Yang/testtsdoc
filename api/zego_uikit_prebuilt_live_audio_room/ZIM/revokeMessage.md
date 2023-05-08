


# revokeMessage method








Future&lt;[ZIMMessageRevokedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageRevokedResult-class.md)> revokeMessage
([ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, [ZIMMessageRevokeConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageRevokeConfig-class.md) config)





<p>Available sinces: 2.5.0 and above.</p>
<p>Detail description: This method implements the function of revoking messages.</p>
<p>Use cases: The user needs to recall a message. This method can be used when the user does not want other users to see the message.</p>
<p>When to call: Called when the message needs to be revoked.</p>
<p>Note: Room message revoke is not supported.</p>
<p>Restrictions: Effective after login.</p>
<p>Related callbacks: If the revoked message is the latest message of the session, the <code>ZIMEventHandler.onConversationChanged</code> callback will be triggered, and if the message is unread, the <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code> callback will be triggered.</p>



## Implementation

```dart
Future<ZIMMessageRevokedResult> revokeMessage (
    ZIMMessage message, ZIMMessageRevokeConfig config);
```







