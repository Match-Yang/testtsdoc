


# setBackgroundMessageHandler method







- @override

Future&lt;[ZegoSignalingPluginSetBackgroundMessageHandlerResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetBackgroundMessageHandlerResult-class.md)> setBackgroundMessageHandler
([ZegoSignalingPluginZPNsBackgroundMessageHandler](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginZPNsBackgroundMessageHandler.md) handler)

_<span class="feature">override</span>_



<p>only for Android</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginSetBackgroundMessageHandlerResult>
    setBackgroundMessageHandler(
  ZegoSignalingPluginZPNsBackgroundMessageHandler handler,
) async {
  ZegoSignalingLoggerService.logInfo(
    'register background message handler',
    tag: 'signaling',
    subTag: 'background message',
  );

  if (!Platform.isAndroid) {
    ZegoSignalingLoggerService.logInfo(
      'Only Support Android Platform.',
      tag: 'signaling',
      subTag: 'background message',
    );

    return ZegoSignalingPluginSetBackgroundMessageHandlerResult(
      error: PlatformException(
        code: '-1',
        message: 'Only Support Android Platform.',
      ),
    );
  }

  ZPNs.setBackgroundMessageHandler(handler);

  return const ZegoSignalingPluginSetBackgroundMessageHandlerResult();
}
```







