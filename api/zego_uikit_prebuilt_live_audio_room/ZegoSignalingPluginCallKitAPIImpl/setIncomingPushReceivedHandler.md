


# setIncomingPushReceivedHandler method







- @override

Future&lt;void> setIncomingPushReceivedHandler
([ZegoSignalingIncomingPushReceivedHandler](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingIncomingPushReceivedHandler.md) handler)

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<void> setIncomingPushReceivedHandler(
  ZegoSignalingIncomingPushReceivedHandler handler,
) async {
  ZegoSignalingLoggerService.logInfo(
    'set incoming push received handler',
    tag: 'signaling',
    subTag: 'callkit',
  );

  CallKitEventHandler.didReceiveIncomingPush = handler;
}
```







