


# callkit property









[ZegoCallKitInterface](../../zego_uikit_prebuilt_live_audio_room/ZegoCallKitInterface-class.md)? callkit
  







## Implementation

```dart
ZegoCallKitInterface? get callkit {
  final ret = plugins[ZegoUIKitPluginType.callkit];
  if (ret == null) {
    debugPrint('callkit is null');
  }
  return ret! as ZegoCallKitInterface;
}
```








