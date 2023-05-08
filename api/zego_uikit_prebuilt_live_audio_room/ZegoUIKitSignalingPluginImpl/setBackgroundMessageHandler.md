


# setBackgroundMessageHandler method








Future&lt;[ZegoSignalingPluginSetBackgroundMessageHandlerResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetBackgroundMessageHandlerResult-class.md)> setBackgroundMessageHandler
([ZegoSignalingPluginZPNsBackgroundMessageHandler](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginZPNsBackgroundMessageHandler.md) handler)

_<span class="feature">inherited</span>_






## Implementation

```dart
Future<ZegoSignalingPluginSetBackgroundMessageHandlerResult>
    setBackgroundMessageHandler(
        ZegoSignalingPluginZPNsBackgroundMessageHandler handler) async {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .setBackgroundMessageHandler(handler);
}
```







