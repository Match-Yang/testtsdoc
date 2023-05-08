


# joinRoom method








Future&lt;[ZegoRoomLoginResult](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomLoginResult-class.md)> joinRoom
(String roomID, {String token = '', bool markAsLargeRoom = false})





<p>join room</p>



## Implementation

```dart
Future<ZegoRoomLoginResult> joinRoom(
  String roomID, {
  String token = '',
  bool markAsLargeRoom = false,
}) async {
  return ZegoUIKitCore.shared.joinRoom(
    roomID,
    markAsLargeRoom: markAsLargeRoom,
  );
}
```







