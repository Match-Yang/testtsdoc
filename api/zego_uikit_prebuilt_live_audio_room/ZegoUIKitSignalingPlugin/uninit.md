


# uninit method







- @override

Future&lt;void> uninit
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<void> uninit() async {
  ZegoSignalingLoggerService.logInfo(
    'destroy ZIM',
    tag: 'signaling',
    subTag: 'init',
  );

  ZIM.getInstance()?.destroy();
}
```







