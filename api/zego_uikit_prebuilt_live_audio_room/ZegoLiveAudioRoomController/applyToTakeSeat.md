


# applyToTakeSeat method








Future&lt;bool> applyToTakeSeat
()





<p>观众主动请求占座位</p>



## Implementation

```dart
Future<bool> applyToTakeSeat() async {
  if (_seatManager?.hostsNotifier.value.isEmpty ?? false) {
    ZegoLoggerService.logInfo(
      'Failed to apply for take seat, host is not exist',
      tag: 'audio room',
      subTag: 'controller',
    );
    return false;
  }

  return ZegoUIKit()
      .getSignalingPlugin()
      .sendInvitation(
        inviterName: ZegoUIKit().getLocalUser().name,
        invitees: _seatManager?.hostsNotifier.value ?? [],
        timeout: 60,
        type: ZegoInvitationType.requestTakeSeat.value,
        data: '',
      )
      .then((ZegoSignalingPluginSendInvitationResult result) {
    ZegoLoggerService.logInfo(
      'apply to take seat finished, code:${result.error?.code}, '
      'message:${result.error?.message}, '
      'invitationID:${result.invitationID}, '
      'errorInvitees:${result.errorInvitees.keys.toList()}',
      tag: 'audio room',
      subTag: 'controller',
    );

    if (result.error != null) {
      _seatManager?.config.onSeatTakingRequestFailed?.call();
    }

    return result.error == null;
  });
}
```







