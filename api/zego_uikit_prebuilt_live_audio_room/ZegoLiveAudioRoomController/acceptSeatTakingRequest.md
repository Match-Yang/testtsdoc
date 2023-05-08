


# acceptSeatTakingRequest method








Future&lt;bool> acceptSeatTakingRequest
(String audienceUserID)





<p>主播接受id为<code>audienceUserID</code>的观众占座位请求</p>



## Implementation

```dart
Future<bool> acceptSeatTakingRequest(String audienceUserID) async {
  return ZegoUIKit()
      .getSignalingPlugin()
      .acceptInvitation(inviterID: audienceUserID, data: '')
      .then((result) {
    ZegoLoggerService.logInfo(
      'accept $audienceUserID seat taking request , result:$result',
      tag: 'live audio',
      subTag: 'controller',
    );
    if (result.error == null) {
      _connectManager?.removeRequestCoHostUsers(
        ZegoUIKit().getUser(audienceUserID) ?? ZegoUIKitUser.empty(),
      );
    } else {
      ZegoLoggerService.logInfo(
        'accept seat taking request error:${result.error}',
        tag: 'audio room',
        subTag: 'controller',
      );
    }

    return result.error == null;
  });
}
```







