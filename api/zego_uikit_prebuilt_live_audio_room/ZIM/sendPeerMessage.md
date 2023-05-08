


# sendPeerMessage method








Future&lt;[ZIMMessageSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)> sendPeerMessage
([ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String toUserID, [ZIMMessageSendConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config)





<p>deprecated: This API has been deprecated since 2.4.0, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a> instead.</p>
<p>Available since: 2.1.5 and above.
Description: After this function is called, a message is sent to the specified user. At the same time, a <code>ZIMMessageSentResult</code> callback is received, which can be used to determine whether the message is sent successfully.
Use cases: This function is used in 1V1 chat scenarios.
Call timing/Notification timing: Can be invoked after login.
Caution: Be aware of the <code>ZIMMessageSentResult</code> callback when sending. This callback can be used to determine if the send fails for some reason.PushConfig Is required only when the offline push function is required.
Usage limit: no more than 10 /s, available after login, unavailable after logout.
Scope of influence: Using this method triggers the <code>ZIMEventHandler.onReceivePeerMessage</code> callback of the message receiver and the <code>ZIMEventHandler.onConversationChanged</code> callback of the sender and receiver. If message DND is not set for the session where the message is sent, Triggers <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code> callback.
Related callbacks:<code>ZIMMessageSentResult</code>、<code>ZIMEventHandler.onReceivePeerMessage</code>、<code>ZIMEventHandler.onConversationChanged</code>、<code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code>.
Related API: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryHistoryMessage.md">queryHistoryMessage</a>、<a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteAllMessage.md">deleteAllMessage</a>、<a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteMessages.md">deleteMessages</a></p>
<p><code>message</code> The message to be sent.
<code>toUserID</code> The ID of the user who will receive the message.
<code>config</code> Related configuration for sending single chat messages.</p>



## Implementation

```dart
/// Description: After this function is called, a message is sent to the specified user. At the same time, a [ZIMMessageSentResult] callback is received, which can be used to determine whether the message is sent successfully.

/// Use cases: This function is used in 1V1 chat scenarios.

/// Call timing/Notification timing: Can be invoked after login.

/// Caution: Be aware of the [ZIMMessageSentResult] callback when sending. This callback can be used to determine if the send fails for some reason.PushConfig Is required only when the offline push function is required.

/// Usage limit: no more than 10 /s, available after login, unavailable after logout.

/// Scope of influence: Using this method triggers the [ZIMEventHandler.onReceivePeerMessage] callback of the message receiver and the [ZIMEventHandler.onConversationChanged] callback of the sender and receiver. If message DND is not set for the session where the message is sent, Triggers [ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated] callback.

/// Related callbacks:[ZIMMessageSentResult]、[ZIMEventHandler.onReceivePeerMessage]、[ZIMEventHandler.onConversationChanged]、[ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated].

/// Related API: [queryHistoryMessage]、[deleteAllMessage]、[deleteMessages]
///
/// [message] The message to be sent.
/// [toUserID] The ID of the user who will receive the message.
/// [config] Related configuration for sending single chat messages.
Future<ZIMMessageSentResult> sendPeerMessage(
    ZIMMessage message, String toUserID, ZIMMessageSendConfig config);
```







