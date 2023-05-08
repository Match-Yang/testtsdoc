


# cancelInvitation method







- @override

Future&lt;[ZegoSignalingPluginCancelInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCancelInvitationResult-class.md)> cancelInvitation
({required String invitationID, required List&lt;String> invitees, String extendedData = ''})

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<ZegoSignalingPluginCancelInvitationResult> cancelInvitation({
  required String invitationID,
  required List<String> invitees,
  String extendedData = '',
}) async {
  ZegoSignalingLoggerService.logInfo(
    'cancel invitation, invitation id:$invitationID, invitees:$invitees, extendedData:$extendedData',
    tag: 'signaling',
    subTag: 'room',
  );

  return ZIM
      .getInstance()!
      .callCancel(invitees, invitationID,
          ZIMCallCancelConfig()..extendedData = extendedData)
      .then((ZIMCallCancelSentResult zimResult) {
    ZegoSignalingLoggerService.logInfo(
      'cancel invitation, done, invitation id:${zimResult.callID}, '
      'error invitees:${zimResult.errorInvitees}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginCancelInvitationResult(
      errorInvitees: zimResult.errorInvitees,
    );
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'cancel invitation, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginCancelInvitationResult(
      errorInvitees: invitees,
      error: error,
    );
  });
}
```







