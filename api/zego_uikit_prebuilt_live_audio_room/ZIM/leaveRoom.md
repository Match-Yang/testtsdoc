


# leaveRoom method








Future&lt;[ZIMRoomLeftResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomLeftResult-class.md)> leaveRoom
(String roomID)





<p>Leave a room.</p>
<p>Available since: 2.1.5 or above.</p>
<p>Description: When users in the room need to leave the room, they can join this room through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/leaveRoom.md">leaveRoom</a>.</p>
<p>Use cases: In the multi-person chat scenario, when users in the room need to leave the room, they can leave the room through this interface.</p>
<p>When to call: After creating a ZIM instance via <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>, it can be called when the user is in the room.</p>
<p>Caution: If the current user is not in this room, the exit fails. When everyone leaves the room, the room will be automatically destroyed.</p>
<p>Related callbacks: The result of leaving the room can be obtained through the <code>ZIMRoomLeftResult</code> callback.</p>
<p>Related APIs: You can create a room through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/createRoom.md">createRoom</a> and join a room with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/joinRoom.md">joinRoom</a>.</p>
<p><code>roomID</code> ID of the room to leave.</p>



## Implementation

```dart
Future<ZIMRoomLeftResult> leaveRoom(String roomID);
```







