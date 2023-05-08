


# disconnectUser method







- @override

Future&lt;[ZegoSignalingPluginDisconnectUserResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginDisconnectUserResult-class.md)> disconnectUser
([Duration timeout = const Duration(seconds: 2)])

_<span class="feature">override</span>_



<p>logout</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginDisconnectUserResult> disconnectUser(
    [Duration timeout = const Duration(seconds: 2)]) async {
  ZegoSignalingLoggerService.logInfo(
    'disconnectUser, current id:${ZegoSignalingPluginCore().currentUser?.userID}, '
    'current name:${ZegoSignalingPluginCore().currentUser?.userName}',
    tag: 'signaling',
    subTag: 'user',
  );

  ZegoSignalingPluginCore().currentUser = null;
  ZIM.getInstance()!.logout();

  if (ZegoSignalingPluginCore().eventCenter.connectionState ==
      ZIMConnectionState.reconnecting) {
    /// if current state is network break(reconnecting),
    /// sdk will not call onConnectionStateChanged callback,
    /// that mean the following Completer code will wait forever,
    /// so here return result directly
    return Future.value(
        const ZegoSignalingPluginDisconnectUserResult(timeout: false));
  }

  /// wait for disconnect, make sure state is disconnected before next connect
  ZegoSignalingLoggerService.logInfo(
    'disconnectUser, waitForDisconnect...',
    tag: 'signaling',
    subTag: 'user',
  );
  if (ZegoSignalingPluginCore().eventCenter.connectionState !=
      ZIMConnectionState.disconnected) {
    final completer = Completer<ZegoSignalingPluginDisconnectUserResult>();
    final timer = Timer.periodic(const Duration(milliseconds: 100), (timer) {
      if (ZegoSignalingPluginCore().eventCenter.connectionState ==
          ZIMConnectionState.disconnected) {
        if (timer.isActive) timer.cancel();
        if (!completer.isCompleted) {
          completer.complete(
              const ZegoSignalingPluginDisconnectUserResult(timeout: false));
        }
        ZegoSignalingLoggerService.logInfo(
          'disconnectUser, waitForDisconnect success',
          tag: 'signaling',
          subTag: 'user',
        );
      }
    });

    /// if not complete in timeout seconds, not wait the disconnect anymore
    Future.delayed(timeout, () {
      if (timer.isActive) timer.cancel();
      if (!completer.isCompleted) {
        completer.complete(
            const ZegoSignalingPluginDisconnectUserResult(timeout: true));
      }
      ZegoSignalingLoggerService.logInfo(
        'disconnectUser, waitForDisconnect timeout',
        tag: 'signaling',
        subTag: 'user',
      );
    });
    return completer.future;
  } else {
    return Future.value(
        const ZegoSignalingPluginDisconnectUserResult(timeout: false));
  }
}
```







