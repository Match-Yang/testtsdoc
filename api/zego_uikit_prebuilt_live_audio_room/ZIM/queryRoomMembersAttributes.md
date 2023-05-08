


# queryRoomMembersAttributes method








Future&lt;[ZIMRoomMembersAttributesQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomMembersAttributesQueriedResult-class.md)> queryRoomMembersAttributes
(List&lt;String> userIDs, String roomID)





<p>Available since:2.4.0 or later.</p>
<p>Description:Call this API to batch query the room user attributes of the members in the room.</p>
<p>Use cases:Use this interface when you need to specify that you want to query some room users.</p>
<p>Restrictions:The maximum call frequency is 5 times within 30 seconds by default, and the maximum query time is 100 people.</p>
<p>Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/setRoomMembersAttributes.md">setRoomMembersAttributes</a>、<a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomMemberAttributesList.md">queryRoomMemberAttributesList</a></p>
<p>Runtime lifecycle: It is available after logging in and joining the corresponding room, but unavailable after leaving the corresponding room.</p>
<p><code>userIDs</code> A list of userIDs to query.
<code>roomID</code>  Room ID.</p>



## Implementation

```dart
Future<ZIMRoomMembersAttributesQueriedResult> queryRoomMembersAttributes(
    List<String> userIDs, String roomID);
```







