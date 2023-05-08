


# sendMessageReceiptsRead method








Future&lt;[ZIMMessageReceiptsReadSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageReceiptsReadSentResult-class.md)> sendMessageReceiptsRead
(List&lt;[ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md)> messageList, String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType)





<p>Available since: 2.5.0 and above.
Description: This method can set the receipt of a batch of messages to become read.
Use cases: Developers can use this method to set a batch of messages with receipts that have been read. If the sender is online, it will receive the <code>onMessageReceiptChanged</code> callback.
When to call: Callable after login. It is recommended to set the settings for the messages that need to be read on the message list page. It is not recommended to mix with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendConversationMessageReceiptRead.md">sendConversationMessageReceiptRead</a>.
Restrictions: Only support the settings for received messages with receipt status as PROCESSING.
Related callbacks: <code>ZIMMessageReceiptsReadSentResult</code>.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a>.</p>



## Implementation

```dart
/// Description: This method can set the receipt of a batch of messages to become read.

/// Use cases: Developers can use this method to set a batch of messages with receipts that have been read. If the sender is online, it will receive the [onMessageReceiptChanged] callback.

/// When to call: Callable after login. It is recommended to set the settings for the messages that need to be read on the message list page. It is not recommended to mix with [sendConversationMessageReceiptRead].

/// Restrictions: Only support the settings for received messages with receipt status as PROCESSING.

/// Related callbacks: [ZIMMessageReceiptsReadSentResult].

/// Related APIs: [sendMessage].
Future<ZIMMessageReceiptsReadSentResult> sendMessageReceiptsRead(
    List<ZIMMessage> messageList, String conversationID, ZIMConversationType conversationType);
```







