


# getRoom method








[ZegoUIKitRoom](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitRoom-class.md) getRoom
()





<p>get room object</p>



## Implementation

```dart
ZegoUIKitRoom getRoom() {
  return ZegoUIKitCore.shared.coreData.room.toUIKitRoom();
}
```







