


# enableNotifyWhenAppRunningInBackgroundOrQuit method







- @override

Future&lt;[ZegoSignalingPluginEnableNotifyResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEnableNotifyResult-class.md)> enableNotifyWhenAppRunningInBackgroundOrQuit
({bool isIOSSandboxEnvironment = false, bool enableIOSVoIP = true, String appName = ''})

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<ZegoSignalingPluginEnableNotifyResult>
    enableNotifyWhenAppRunningInBackgroundOrQuit({
  bool isIOSSandboxEnvironment = false,
  bool enableIOSVoIP = true,
  String appName = '',
}) async {
  ZegoSignalingLoggerService.logInfo(
    'enable Notify When App Running In Background Or Quit, '
    'is iOS Sandbox Environment:$isIOSSandboxEnvironment, '
    'enable iOS VoIP:$enableIOSVoIP, '
    'appName: $appName',
    tag: 'signaling',
    subTag: 'notification',
  );

  if ((!Platform.isAndroid) && (!Platform.isIOS)) {
    ZegoSignalingLoggerService.logInfo(
      'Only Support Android And iOS Platform.',
      tag: 'signaling',
      subTag: 'notification',
    );

    return ZegoSignalingPluginEnableNotifyResult(
      error: PlatformException(
        code: '-1',
        message: 'Only Support Android And iOS Platform.',
      ),
    );
  }

  try {
    if (Platform.isAndroid) {
      await ZPNs.setPushConfig(ZPNsConfig()..enableFCMPush = true);
    } else if (Platform.isIOS) {
      await ZPNs.getInstance().applyNotificationPermission();

      if (enableIOSVoIP) {
        CallKit.setInitConfiguration(
          CXProviderConfiguration(localizedName: appName),
        );
      }
    }

    await ZPNs.getInstance().registerPush(
      iOSEnvironment: isIOSSandboxEnvironment
          ? ZPNsIOSEnvironment.Development
          : ZPNsIOSEnvironment.Production,
      enableIOSVoIP: enableIOSVoIP,
    );
    ZegoSignalingLoggerService.logInfo(
      'register push done',
      tag: 'signaling',
      subTag: 'notification',
    );
    return const ZegoSignalingPluginEnableNotifyResult();
  } catch (e) {
    ZegoSignalingLoggerService.logInfo(
      'register push, error:${e.toString()}',
      tag: 'signaling',
      subTag: 'notification',
    );

    if (e is PlatformException) {
      return ZegoSignalingPluginEnableNotifyResult(
        error: PlatformException(
          code: e.code,
          message: e.message,
        ),
      );
    } else {
      return ZegoSignalingPluginEnableNotifyResult(
        error: PlatformException(
          code: '-2',
          message: e.toString(),
        ),
      );
    }
  }
}
```







