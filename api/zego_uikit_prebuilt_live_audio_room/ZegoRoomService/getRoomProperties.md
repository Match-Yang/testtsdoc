


# getRoomProperties method








Map&lt;String, [RoomProperty](../../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)> getRoomProperties
()





<p>get room properties</p>



## Implementation

```dart
Map<String, RoomProperty> getRoomProperties() {
  return Map<String, RoomProperty>.from(
      ZegoUIKitCore.shared.coreData.room.properties);
}
```







