


# queryRoomMemberAttributesList method








Future&lt;[ZIMRoomMemberAttributesListQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberAttributesListQueriedResult-class.md)> queryRoomMemberAttributesList
(String roomID, [ZIMRoomMemberAttributesQueryConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberAttributesQueryConfig-class.md) config)





<p>Available since:2.4.0 or later.</p>
<p>Description:Call the API to paginate the room user properties that have room property members in the room.</p>
<p>Use cases:This interface is used when you need to query all room users.</p>
<p>Restrictions:The maximum call frequency is 5 times within 30 seconds by default, and the maximum query time is 100 people.</p>
<p>Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/setRoomMembersAttributes.md">setRoomMembersAttributes</a>、<a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomMembersAttributes.md">queryRoomMembersAttributes</a></p>
<p>Runtime lifecycle: It is available after logging in and joining the corresponding room, but unavailable after leaving the corresponding room.</p>
<p><code>roomID</code>  Room ID.
<code>config</code>  Behavior configuration of the operation.</p>



## Implementation

```dart
Future<ZIMRoomMemberAttributesListQueriedResult>
    queryRoomMemberAttributesList(
        String roomID, ZIMRoomMemberAttributesQueryConfig config);
```







