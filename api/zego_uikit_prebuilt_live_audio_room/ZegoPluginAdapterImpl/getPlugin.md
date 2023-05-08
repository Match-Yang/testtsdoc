


# getPlugin method








[IZegoUIKitPlugin](../../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin-mixin.md)? getPlugin
([ZegoUIKitPluginType](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPluginType.md) type)








## Implementation

```dart
IZegoUIKitPlugin? getPlugin(ZegoUIKitPluginType type) {
  debugPrint('getPlugin: $type');
  return plugins[type];
}
```







