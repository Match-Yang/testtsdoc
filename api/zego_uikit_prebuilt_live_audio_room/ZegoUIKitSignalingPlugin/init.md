


# init method







- @override

Future&lt;void> init
({required int appID, String appSign = ''})

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<void> init({required int appID, String appSign = ''}) async {
  await ZegoSignalingLoggerService().initLog();

  ZegoSignalingLoggerService.logInfo(
    'create ZIM',
    tag: 'signaling',
    subTag: 'init',
  );

  ZIM.create(ZIMAppConfig()
    ..appID = appID
    ..appSign = appSign);
}
```







