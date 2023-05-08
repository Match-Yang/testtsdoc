


# joinRoom method







- @override

Future&lt;[ZegoSignalingPluginJoinRoomResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginJoinRoomResult-class.md)> joinRoom
({required String roomID, required String roomName, Map&lt;String, String> roomAttributes = const {}, int roomDestroyDelayTime = 0})

_<span class="feature">override</span>_



<p>join room</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginJoinRoomResult> joinRoom({
  required String roomID,
  required String roomName,
  Map<String, String> roomAttributes = const {},
  int roomDestroyDelayTime = 0,
}) async {
  ZegoSignalingLoggerService.logInfo(
    'join room, room id:$roomID, room name:$roomName',
    tag: 'signaling',
    subTag: 'room',
  );

  return ZIM
      .getInstance()!
      .enterRoom(
        ZIMRoomInfo()
          ..roomID = roomID
          ..roomName = roomName,
        ZIMRoomAdvancedConfig()
          ..roomAttributes = roomAttributes
          ..roomDestroyDelayTime = roomDestroyDelayTime,
      )
      .then((zimResult) {
    ZegoSignalingLoggerService.logInfo(
      'join room finish',
      tag: 'signaling',
      subTag: 'room',
    );

    assert(zimResult.roomInfo.baseInfo.roomID.isNotEmpty,
        'zimResult.roomInfo.baseInfo.roomID.isNotEmpty');

    return const ZegoSignalingPluginJoinRoomResult();
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'join room, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginJoinRoomResult(
      error: error,
    );
  });
}
```







