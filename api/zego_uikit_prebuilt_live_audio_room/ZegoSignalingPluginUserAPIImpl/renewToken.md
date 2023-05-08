


# renewToken method







- @override

Future&lt;[ZegoSignalingPluginRenewTokenResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRenewTokenResult-class.md)> renewToken
(String token)

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<ZegoSignalingPluginRenewTokenResult> renewToken(String token) async {
  ZegoSignalingLoggerService.logInfo(
    'renewToken, token:$token',
    tag: 'signaling',
    subTag: 'user',
  );

  return ZIM
      .getInstance()!
      .renewToken(token)
      .then((value) => const ZegoSignalingPluginRenewTokenResult())
      .catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'renewToken error:${error.toString()}',
      tag: 'signaling',
      subTag: 'user',
    );

    return ZegoSignalingPluginRenewTokenResult(
      error: error,
    );
  });
}
```







