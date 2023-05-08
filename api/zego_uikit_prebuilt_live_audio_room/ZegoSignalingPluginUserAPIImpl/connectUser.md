


# connectUser method







- @override

Future&lt;[ZegoSignalingPluginConnectUserResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginConnectUserResult-class.md)> connectUser
({required String id, String name = ''})

_<span class="feature">override</span>_



<p>login</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginConnectUserResult> connectUser({
  required String id,
  String name = '',
}) async {
  ZegoSignalingLoggerService.logInfo(
    'connectUser, id:$id, name:$name',
    tag: 'signaling',
    subTag: 'user',
  );

  var targetUser = ZIMUserInfo()
    ..userID = id
    ..userName = name.isNotEmpty ? name : id;

  return ZIM.getInstance()!.login(targetUser).then((value) {
    ZegoSignalingLoggerService.logInfo(
      'connectUser success.',
      tag: 'signaling',
      subTag: 'user',
    );

    ZegoSignalingPluginCore().currentUser = targetUser;

    return const ZegoSignalingPluginConnectUserResult();
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'connectUser, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'user',
    );

    if (error is PlatformException &&
        int.parse(error.code) ==
            ZIMErrorCode.networkModuleUserHasAlreadyLogged &&
        ZegoSignalingPluginCore().currentUser?.userID == targetUser.userID &&
        ZegoSignalingPluginCore().currentUser?.userName ==
            targetUser.userName) {
      ZegoSignalingLoggerService.logInfo(
        'connectUser, user is same who current login',
        tag: 'signaling',
        subTag: 'user',
      );

      return const ZegoSignalingPluginConnectUserResult();
    }

    return ZegoSignalingPluginConnectUserResult(
      error: error,
    );
  });
}
```







