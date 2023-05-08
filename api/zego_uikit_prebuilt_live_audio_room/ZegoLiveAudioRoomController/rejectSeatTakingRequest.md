


# rejectSeatTakingRequest method








Future&lt;bool> rejectSeatTakingRequest
(String audienceUserID)





<p>主播拒绝id为<code>audienceUserID</code>的观众占座位请求</p>



## Implementation

```dart
Future<bool> rejectSeatTakingRequest(String audienceUserID) async {
  return ZegoUIKit()
      .getSignalingPlugin()
      .refuseInvitation(inviterID: audienceUserID, data: '')
      .then((result) {
    ZegoLoggerService.logInfo(
      'refuse audience $audienceUserID link request, $result',
      tag: 'live audio',
      subTag: 'controller',
    );

    if (result.error == null) {
      _connectManager?.removeRequestCoHostUsers(
        ZegoUIKit().getUser(audienceUserID) ?? ZegoUIKitUser.empty(),
      );
    } else {
      ZegoLoggerService.logInfo(
        'reject seat taking request error:${result.error}',
        tag: 'audio room',
        subTag: 'controller',
      );
    }

    return result.error == null;
  });
}
```







