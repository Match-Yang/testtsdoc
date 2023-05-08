


# acceptHostTakeSeatInvitation method








Future&lt;bool> acceptHostTakeSeatInvitation
({required BuildContext context})





<p>接受主持人占座邀请。其中<code>context</code> 为Flutter上下文对象</p>



## Implementation

```dart
Future<bool> acceptHostTakeSeatInvitation({
  required BuildContext context,
}) async {
  return ZegoUIKit()
      .getSignalingPlugin()
      .acceptInvitation(
        inviterID: _seatManager?.hostsNotifier.value.first ?? '',
        data: '',
      )
      .then((result) async {
    ZegoLoggerService.logInfo(
      'accept host take seat invitation, result:$result',
      tag: 'live audio',
      subTag: 'controller',
    );

    if (result.error != null) {
      ZegoLoggerService.logInfo(
        'accept host take seat invitation error: ${result.error}',
        tag: 'live audio',
        subTag: 'controller',
      );
      return false;
    }

    return requestPermissions(
      context: context,
      isShowDialog: true,
      innerText: _seatManager?.innerText ?? ZegoInnerText(),
    ).then((_) async {
      /// agree host's host, take seat, find the nearest seat index
      return await _seatManager
              ?.takeOnSeat(
            _seatManager?.getNearestEmptyIndex() ?? -1,
            isForce: false,
            isDeleteAfterOwnerLeft: true,
          )
              .then((result) async {
            if (result) {
              ZegoUIKit().turnMicrophoneOn(true);
            }

            return result;
          }) ??
          false;
    });
  });
}
```







