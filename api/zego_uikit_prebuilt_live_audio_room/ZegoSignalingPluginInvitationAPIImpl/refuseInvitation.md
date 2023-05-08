


# refuseInvitation method







- @override

Future&lt;[ZegoSignalingPluginResponseInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)> refuseInvitation
({required String invitationID, String extendedData = ''})

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<ZegoSignalingPluginResponseInvitationResult> refuseInvitation({
  required String invitationID,
  String extendedData = '',
}) {
  ZegoSignalingLoggerService.logInfo(
    'refuse invitation, invitation id:$invitationID, extendedData:$extendedData',
    tag: 'signaling',
    subTag: 'room',
  );

  return ZIM
      .getInstance()!
      .callReject(
          invitationID, ZIMCallRejectConfig()..extendedData = extendedData)
      .then((ZIMCallRejectionSentResult zimResult) {
    ZegoSignalingLoggerService.logInfo(
      'refuse invitation, done, invitation id:${zimResult.callID}',
      tag: 'signaling',
      subTag: 'room',
    );

    return const ZegoSignalingPluginResponseInvitationResult();
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'refuse invitation, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginResponseInvitationResult(
      error: error,
    );
  });
}
```







