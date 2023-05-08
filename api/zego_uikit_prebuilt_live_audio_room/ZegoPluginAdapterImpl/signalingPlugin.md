


# signalingPlugin property









[ZegoSignalingPluginInterface](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInterface-class.md)? signalingPlugin
  







## Implementation

```dart
ZegoSignalingPluginInterface? get signalingPlugin {
  final ret = plugins[ZegoUIKitPluginType.signaling];
  if (ret == null) {
    debugPrint('signalingPlugin is null');
  }
  return ret! as ZegoSignalingPluginInterface;
}
```








