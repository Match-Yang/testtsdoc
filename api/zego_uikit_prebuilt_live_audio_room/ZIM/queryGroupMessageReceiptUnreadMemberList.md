


# queryGroupMessageReceiptUnreadMemberList method








Future&lt;[ZIMGroupMessageReceiptMemberListQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupMessageReceiptMemberListQueriedResult-class.md)> queryGroupMessageReceiptUnreadMemberList
([ZIMMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String groupID, [ZIMGroupMessageReceiptMemberQueryConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupMessageReceiptMemberQueryConfig-class.md) config)





<p>Available since: 2.5.0 and above.</p>
<p>Description: This method can query the specific unread member list of a message sent by a group.</p>
<p>Use cases: Developers can use this method to query the specific unread member list of a message they send.</p>
<p>When to call: Callable after login.</p>
<p>Restrictions: only supports querying the messages sent by the local end, and the receipt status of the messages is not NONE and UNKNOWN. If the user is not in the group, or has been kicked out of the group, the corresponding member list cannot be found.</p>
<p>Related callbacks: <code>ZIMGroupMessageReceiptMemberListQueriedResult</code>.</p>
<p>Related APIs: If you need to query the receipt status of a certain message or only need to query the read/unread count, you can query through the interface <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryMessageReceiptsInfo.md">queryMessageReceiptsInfo</a>.</p>



## Implementation

```dart
Future<ZIMGroupMessageReceiptMemberListQueriedResult> queryGroupMessageReceiptUnreadMemberList (
    ZIMMessage message, String groupID, ZIMGroupMessageReceiptMemberQueryConfig config);
```







