


# queryRoomOnlineMemberCount method








Future&lt;[ZIMRoomOnlineMemberCountQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomOnlineMemberCountQueriedResult-class.md)> queryRoomOnlineMemberCount
(String roomID)





<p>Query the number of online members in the room.</p>
<p>Available since: 2.1.5 or above.</p>
<p>Description: After joining a room, you can use this function to get the number of online members in the room.</p>
<p>Use cases: When a developer needs to obtain the number of room members who are online, this interface can be called.</p>
<p>Calling time: After creating a ZIM instance through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>, and the user is in the room that needs to be queried, this interface can be called.</p>
<p>Caution: If the user is not currently in this room, the query will fail.</p>
<p>Related APIs: the room member can be inquired through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomMemberList.md">queryRoomMemberList</a>.</p>
<p><code>roomID</code> ID of the room to query.</p>



## Implementation

```dart
Future<ZIMRoomOnlineMemberCountQueriedResult> queryRoomOnlineMemberCount(
    String roomID);
```







