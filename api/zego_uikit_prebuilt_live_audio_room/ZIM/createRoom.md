


# createRoom method








Future&lt;[ZIMRoomCreatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomCreatedResult-class.md)> createRoom
([ZIMRoomInfo](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomInfo-class.md) roomInfo, [[ZIMRoomAdvancedConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomAdvancedConfig-class.md)? config])





<p>Create a room.</p>
<p>Available since: 2.1.5 or above.</p>
<p>Description: When a room is created, other users can join this room through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/joinRoom.md">joinRoom</a> function.</p>
<p>Use cases: When you need to create a multi-person chat scene, you can create a room by this API.</p>
<p>When to call: It can be called after creating a ZIM instance through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>.</p>
<p>Caution: When everyone leaves the room, the room will be automatically destroyed.</p>
<p>Related callbacks: The result of the room creation can be obtained through the <code>ZIMRoomCreatedResult</code> callback.</p>
<p>Related APIs: You can join the room through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/joinRoom.md">joinRoom</a> and leave the room with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/leaveRoom.md">leaveRoom</a>.</p>
<p><code>roomInfo</code> The configuration information of the room to be created.
<code>config</code> The advanced information of the room to be created.</p>



## Implementation

```dart
Future<ZIMRoomCreatedResult> createRoom(ZIMRoomInfo roomInfo,
    [ZIMRoomAdvancedConfig? config]);
```







