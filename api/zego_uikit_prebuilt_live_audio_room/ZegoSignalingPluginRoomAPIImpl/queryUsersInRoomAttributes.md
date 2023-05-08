


# queryUsersInRoomAttributes method







- @override

Future&lt;[ZegoSignalingPluginQueryUsersInRoomAttributesResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryUsersInRoomAttributesResult-class.md)> queryUsersInRoomAttributes
({required String roomID, int count = 100, String nextFlag = ''})

_<span class="feature">override</span>_



<p>query users in room attributes</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginQueryUsersInRoomAttributesResult>
    queryUsersInRoomAttributes({
  required String roomID,
  int count = 100,
  String nextFlag = '',
}) {
  return ZIM
      .getInstance()!
      .queryRoomMemberAttributesList(
        roomID,
        ZIMRoomMemberAttributesQueryConfig()
          ..count = count
          ..nextFlag = nextFlag,
      )
      .then((zimResult) {
    return ZegoSignalingPluginQueryUsersInRoomAttributesResult(
      nextFlag: zimResult.nextFlag,
      attributes: {
        for (var element in zimResult.infos)
          element.userID: element.attributes
      },
    );
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'query user in-room attributes, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginQueryUsersInRoomAttributesResult(
      error: error,
      nextFlag: '',
      attributes: const {},
    );
  });
}
```







