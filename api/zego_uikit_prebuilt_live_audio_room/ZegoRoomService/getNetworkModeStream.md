


# getNetworkModeStream method








Stream&lt;[ZegoNetworkMode](../../zego_uikit_prebuilt_live_audio_room/ZegoNetworkMode.md)> getNetworkModeStream
()





<p>get network state notifier</p>



## Implementation

```dart
Stream<ZegoNetworkMode> getNetworkModeStream() {
  return ZegoUIKitCore.shared.coreData.networkModeStreamCtrl.stream;
}
```







