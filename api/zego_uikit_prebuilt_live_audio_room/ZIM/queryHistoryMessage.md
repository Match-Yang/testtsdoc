


# queryHistoryMessage method








Future&lt;[ZIMMessageQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageQueriedResult-class.md)> queryHistoryMessage
(String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageQueryConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageQueryConfig-class.md) config)





<p>Supported versions: 2.1.5 and above.
Detailed description: This method is used to query historical messages.
Business scenario: When you need to obtain past historical messages, you can call this interface to query historical messages by paging.
Call timing/Notification timing: Called when historical messages need to be queried.
Restrictions: Effective after login, invalid after logout.</p>
<p><code>conversationID</code> The session ID of the queried historical message.
<code>conversationType</code> The type of the queried historical message.
<code>config</code>  Query the configuration of historical messages.</p>



## Implementation

```dart
/// Detailed description: This method is used to query historical messages.

/// Business scenario: When you need to obtain past historical messages, you can call this interface to query historical messages by paging.

/// Call timing/Notification timing: Called when historical messages need to be queried.

/// Restrictions: Effective after login, invalid after logout.

///
/// [conversationID] The session ID of the queried historical message.
/// [conversationType] The type of the queried historical message.
/// [config]  Query the configuration of historical messages.
Future<ZIMMessageQueriedResult> queryHistoryMessage(String conversationID,
    ZIMConversationType conversationType, ZIMMessageQueryConfig config);
```







