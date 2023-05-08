


# sendConversationMessageReceiptRead method








Future&lt;[ZIMConversationMessageReceiptReadSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationMessageReceiptReadSentResult-class.md)> sendConversationMessageReceiptRead
(String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType)





<p>Available since: 2.5.0 and above.</p>
<p>Description: Set all received receipts of the conversation to be read.</p>
<p>Use cases: Set all received receipt messages in the entire conversation to be read, and the sender of the message receipt in the conversation will receive the <code>onConversationMessageReceiptChanged</code> callback from ZIMEventHandler.</p>
<p>When to call: It can be called after login. It is recommended to call before entering the message list page. In the message list page, it is recommended to call <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessageReceiptsRead.md">sendMessageReceiptsRead</a> to batch set the messages that need to be read.</p>
<p>Caution: Only single chat conversation are allowed.</p>
<p>Related callback: <code>ZIMConversationMessageReceiptReadSentResult</code>.</p>
<p>Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessageReceiptsRead.md">sendMessageReceiptsRead</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a>.</p>



## Implementation

```dart
Future<ZIMConversationMessageReceiptReadSentResult> sendConversationMessageReceiptRead(
    String conversationID, ZIMConversationType conversationType);
```







