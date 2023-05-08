


# queryMessageReceiptsInfo method








Future&lt;[ZIMMessageReceiptsInfoQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMessageReceiptsInfoQueriedResult-class.md)> queryMessageReceiptsInfo
(List&lt;[ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md)> messageList, String conversationID, [ZIMConversationType](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType)





<p>Available since: 2.5.0 and above.</p>
<p>Description: This method can query the receipt information of a batch of messages, including the status, the number of unread users and the number of read users.</p>
<p>Use cases: If you need to query the receipt status of the message, the number of unread users and the number of read users, you can call this interface.</p>
<p>When to call: Callable after login. If you need to query the detailed member list, you can query through the interface <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMessageReceiptReadMemberList.md">queryGroupMessageReceiptReadMemberList</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMessageReceiptUnreadMemberList.md">queryGroupMessageReceiptUnreadMemberList</a>.</p>
<p>Restrictions: Only messages whose statuses are not NONE and UNKNOWN are supported.</p>
<p>Related callbacks: <code>ZIMMessageReceiptsInfoQueriedResult</code>.</p>
<p>Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMessageReceiptReadMemberList.md">queryGroupMessageReceiptReadMemberList</a> , <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMessageReceiptUnreadMemberList.md">queryGroupMessageReceiptUnreadMemberList</a>.</p>



## Implementation

```dart
Future<ZIMMessageReceiptsInfoQueriedResult> queryMessageReceiptsInfo(
    List<ZIMMessage> messageList, String conversationID, ZIMConversationType conversationType);
```







