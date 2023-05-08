


# enterRoom method








Future&lt;[ZIMRoomEnteredResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomEnteredResult-class.md)> enterRoom
([ZIMRoomInfo](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomInfo-class.md) roomInfo, [ZIMRoomAdvancedConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomAdvancedConfig-class.md) config)





<p>Supported version: 2.1.5.</p>
<p>Detail description: After calling this API, ZIM will decide whether to create a room or join a room according to whether the user is the first to enter. At the same time, if the first user to enter has room advanced attributes, those attributes will take effect.</p>
<p>Business scenario: When you need to enter a multi-person chat scene with custom attributes, and you do not need to distinguish whether the room is created or added, you can enter a room through this interface.</p>
<p>When to call: It can be called after logging in.</p>
<p>Note: When everyone leaves the room, the room will be automatically destroyed, and a user can be in a maximum of 5 rooms at the same time. <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/enterRoom.md">enterRoom</a> is equivalent to <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/createRoom.md">createRoom</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/joinRoom.md">joinRoom</a>, so you only need to choose one of the APIs.</p>
<p>Related callbacks: The result of entering the room can be obtained through the <code>ZIMRoomEnteredResult</code> callback.</p>
<p>Related interface: You can enter the room through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/enterRoom.md">enterRoom</a>, and leave the room through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/leaveRoom.md">leaveRoom</a>.</p>



## Implementation

```dart
Future<ZIMRoomEnteredResult> enterRoom(
    ZIMRoomInfo roomInfo, ZIMRoomAdvancedConfig config);
```







