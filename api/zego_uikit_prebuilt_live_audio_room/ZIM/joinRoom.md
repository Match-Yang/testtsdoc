


# joinRoom method








Future&lt;[ZIMRoomJoinedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomJoinedResult-class.md)> joinRoom
(String roomID)





<p>Join a room.</p>
<p>Available since: 2.1.5 or above.</p>
<p>Description: If the room does not exist, the join fails and you need to call <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/createRoom.md">createRoom</a> to create the room first.</p>
<p>Use cases: In a multi-person chat scenario, users can call this interface to enter the room when they need to join the room.</p>
<p>When to call: It can be called after creating a ZIM instance through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>.</p>
<p>Caution: When everyone leaves the room, the room will be automatically destroyed.</p>
<p>Related callbacks: The result of joining the room can be obtained through the <code>ZIMRoomJoinedResult</code> callback.</p>
<p>Related APIs: You can create a room with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/createRoom.md">createRoom</a> and leave the room with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/leaveRoom.md">leaveRoom</a>.</p>
<p><code>roomID</code> ID of the room to join.</p>



## Implementation

```dart
Future<ZIMRoomJoinedResult> joinRoom(String roomID);
```







