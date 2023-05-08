


# acceptInvitation method







- @override

Future&lt;[ZegoSignalingPluginResponseInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)> acceptInvitation
({required String invitationID, String extendedData = ''})

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<ZegoSignalingPluginResponseInvitationResult> acceptInvitation({
  required String invitationID,
  String extendedData = '',
}) {
  ZegoSignalingLoggerService.logInfo(
    'accept invitation, invitation id:$invitationID, extendedData:$extendedData',
    tag: 'signaling',
    subTag: 'room',
  );

  return ZIM
      .getInstance()!
      .callAccept(
          invitationID, ZIMCallAcceptConfig()..extendedData = extendedData)
      .then((ZIMCallAcceptanceSentResult zimResult) {
    ZegoSignalingLoggerService.logInfo(
      'accept invitation, done, invitation id:${zimResult.callID}',
      tag: 'signaling',
      subTag: 'room',
    );

    return const ZegoSignalingPluginResponseInvitationResult();
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'accept invitation, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginResponseInvitationResult(
      error: error,
    );
  });
}
```







