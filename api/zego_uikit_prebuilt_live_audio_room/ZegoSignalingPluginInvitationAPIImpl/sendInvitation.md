


# sendInvitation method







- @override

Future&lt;[ZegoSignalingPluginSendInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSendInvitationResult-class.md)> sendInvitation
({required List&lt;String> invitees, required int timeout, String extendedData = '', [ZegoSignalingPluginNotificationConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationConfig-class.md)? notificationConfig})

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<ZegoSignalingPluginSendInvitationResult> sendInvitation({
  required List<String> invitees,
  required int timeout,
  String extendedData = '',
  ZegoSignalingPluginNotificationConfig? notificationConfig,
}) async {
  ZegoSignalingLoggerService.logInfo(
    'send invitation, invitees:$invitees, '
    'timeout:$timeout, '
    'extendedData:$extendedData, '
    'notification config:${notificationConfig.toString()}',
    tag: 'signaling',
    subTag: 'room',
  );

  final config = ZIMCallInviteConfig()
    ..extendedData = extendedData
    ..timeout = timeout
    ..pushConfig = (notificationConfig != null)
        ? (ZIMPushConfig()
          ..title = notificationConfig.title
          ..content = notificationConfig.message
          ..resourcesID = notificationConfig.resourceID
          ..payload = notificationConfig.payload)
        : null;

  return ZIM
      .getInstance()!
      .callInvite(invitees, config)
      .then((ZIMCallInvitationSentResult zimResult) {
    ZegoSignalingLoggerService.logInfo(
      'send invitation, done, invitation id:${zimResult.callID}, '
      'error invitees:${zimResult.info.errorInvitees.map((e) => '${e.userID}, ')}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginSendInvitationResult(
      invitationID: zimResult.callID,
      errorInvitees: {
        for (var element in zimResult.info.errorInvitees)
          element.userID:
              ZegoSignalingPluginCallUserState.values[element.state.index]
      },
    );
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'send invitation, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginSendInvitationResult(
      invitationID: '',
      errorInvitees: {},
      error: error,
    );
  });
}
```







