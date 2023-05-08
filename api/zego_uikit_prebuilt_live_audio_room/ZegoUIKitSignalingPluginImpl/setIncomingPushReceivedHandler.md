


# setIncomingPushReceivedHandler method








Future&lt;void> setIncomingPushReceivedHandler
([ZegoSignalingIncomingPushReceivedHandler](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingIncomingPushReceivedHandler.md) handler)

_<span class="feature">inherited</span>_






## Implementation

```dart
Future<void> setIncomingPushReceivedHandler(
    ZegoSignalingIncomingPushReceivedHandler handler) async {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .setIncomingPushReceivedHandler(handler);
}
```







