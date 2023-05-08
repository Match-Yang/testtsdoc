


# queryRoomMemberList method








Future&lt;[ZIMRoomMemberQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult-class.md)> queryRoomMemberList
(String roomID, [ZIMRoomMemberQueryConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueryConfig-class.md) config)





<p>Query the list of members in the room.</p>
<p>Available since: 2.1.5 or above.</p>
<p>Description: After joining a room, you can use this function to get the list of members in the room.</p>
<p>Use cases: When a developer needs to obtain a list of room members for other business operations, this interface can be called to obtain a list of members.</p>
<p>When to call: After creating a ZIM instance through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>, and the user is in the room that needs to be queried, you can call this interface.</p>
<p>Caution: If the user is not currently in this room, the query fails.</p>
<p>Related callbacks: Through the <code>ZIMRoomMemberQueriedResult</code> callback, you can get the result of querying the room member list.</p>
<p>Related APIs: You can check the online number of people in the room through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomOnlineMemberCount.md">queryRoomOnlineMemberCount</a>.</p>
<p><code>roomID</code> ID of the room to query.
<code>config</code> Configuration of query room member operation.</p>



## Implementation

```dart
Future<ZIMRoomMemberQueriedResult> queryRoomMemberList(
    String roomID, ZIMRoomMemberQueryConfig config);
```







