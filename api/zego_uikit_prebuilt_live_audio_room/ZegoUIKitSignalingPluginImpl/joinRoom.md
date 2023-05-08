


# joinRoom method








Future&lt;[ZegoSignalingPluginJoinRoomResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginJoinRoomResult-class.md)> joinRoom
(String roomID, {String roomName = ''})





<p>join room</p>



## Implementation

```dart
Future<ZegoSignalingPluginJoinRoomResult> joinRoom(String roomID,
    {String roomName = ''}) async {
  return ZegoSignalingPluginCore.shared.joinRoom(roomID, roomName);
}
```







