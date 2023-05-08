


# leaveRoom method







- @override

Future&lt;[ZegoSignalingPluginLeaveRoomResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginLeaveRoomResult-class.md)> leaveRoom
({required String roomID})

_<span class="feature">override</span>_



<p>leave room</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginLeaveRoomResult> leaveRoom({
  required String roomID,
}) async {
  ZegoSignalingLoggerService.logInfo(
    'leave room, room id:$roomID',
    tag: 'signaling',
    subTag: 'room',
  );

  return ZIM
      .getInstance()!
      .leaveRoom(roomID)
      .then((value) => const ZegoSignalingPluginLeaveRoomResult())
      .catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'leave room, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginLeaveRoomResult(
      error: error,
    );
  });
}
```







