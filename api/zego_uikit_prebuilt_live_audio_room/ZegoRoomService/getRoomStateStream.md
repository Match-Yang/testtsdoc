


# getRoomStateStream method








ValueNotifier&lt;[ZegoUIKitRoomState](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitRoomState-class.md)> getRoomStateStream
()





<p>get room state notifier</p>



## Implementation

```dart
ValueNotifier<ZegoUIKitRoomState> getRoomStateStream() {
  return ZegoUIKitCore.shared.coreData.room.state;
}
```







