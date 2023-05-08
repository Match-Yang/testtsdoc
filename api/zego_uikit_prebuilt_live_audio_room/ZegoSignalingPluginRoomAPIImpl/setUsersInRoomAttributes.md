


# setUsersInRoomAttributes method







- @override

Future&lt;[ZegoSignalingPluginSetUsersInRoomAttributesResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetUsersInRoomAttributesResult-class.md)> setUsersInRoomAttributes
({required String roomID, required List&lt;String> userIDs, required Map&lt;String, String> setAttributes, bool isDeleteAfterOwnerLeft = true})

_<span class="feature">override</span>_



<p>set users in room attributes</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginSetUsersInRoomAttributesResult>
    setUsersInRoomAttributes({
  required String roomID,
  required List<String> userIDs,
  required Map<String, String> setAttributes,
  bool isDeleteAfterOwnerLeft = true,
}) {
  return ZIM
      .getInstance()!
      .setRoomMembersAttributes(
          setAttributes,
          userIDs,
          roomID,
          ZIMRoomMemberAttributesSetConfig()
            ..isDeleteAfterOwnerLeft = isDeleteAfterOwnerLeft)
      .then((ZIMRoomMembersAttributesOperatedResult zimResult) {
    return ZegoSignalingPluginSetUsersInRoomAttributesResult(
      errorUserList: zimResult.errorUserList,
      errorKeys: {
        for (var element in zimResult.infos)
          element.attributesInfo.userID: element.errorKeys
      },
      attributes: {
        for (var element in zimResult.infos)
          element.attributesInfo.userID: element.attributesInfo.attributes
      },
    );
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'set user in-room attributes, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginSetUsersInRoomAttributesResult(
      error: error,
      errorUserList: userIDs,
      attributes: {},
      errorKeys: {},
    );
  });
}
```







