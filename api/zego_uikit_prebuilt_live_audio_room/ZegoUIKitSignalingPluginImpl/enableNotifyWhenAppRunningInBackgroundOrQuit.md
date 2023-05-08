


# enableNotifyWhenAppRunningInBackgroundOrQuit method








Future&lt;[ZegoSignalingPluginEnableNotifyResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEnableNotifyResult-class.md)> enableNotifyWhenAppRunningInBackgroundOrQuit
(bool enabled, {bool isIOSSandboxEnvironment = false, bool enableIOSVoIP = true, String appName = ''})

_<span class="feature">inherited</span>_



<p>enable notification</p>



## Implementation

```dart
Future<ZegoSignalingPluginEnableNotifyResult>
    enableNotifyWhenAppRunningInBackgroundOrQuit(
  bool enabled, {
  bool isIOSSandboxEnvironment = false,
  bool enableIOSVoIP = true,
  String appName = '',
}) {
  return ZegoSignalingPluginCore.shared.coreData
      .enableNotifyWhenAppRunningInBackgroundOrQuit(
    enabled,
    isIOSSandboxEnvironment: isIOSSandboxEnvironment,
    enableIOSVoIP: enableIOSVoIP,
    appName: appName,
  );
}
```







