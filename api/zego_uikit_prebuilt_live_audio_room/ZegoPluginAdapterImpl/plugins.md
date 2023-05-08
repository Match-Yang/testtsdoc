


# plugins property







Map&lt;[ZegoUIKitPluginType](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPluginType.md), [IZegoUIKitPlugin](../../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin-mixin.md)?> plugins
  
_<span class="feature">read / write</span>_






## Implementation

```dart
Map<ZegoUIKitPluginType, IZegoUIKitPlugin?> plugins = {
  for (var type in ZegoUIKitPluginType.values) type: null
};
```







