


# getReceiveSEIStream method








Stream&lt;[ZegoUIKitReceiveSEIEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitReceiveSEIEvent-class.md)> getReceiveSEIStream
()








## Implementation

```dart
Stream<ZegoUIKitReceiveSEIEvent> getReceiveSEIStream() {
  return ZegoUIKitCore.shared.coreData.receiveSEIStreamCtrl.stream;
}
```







