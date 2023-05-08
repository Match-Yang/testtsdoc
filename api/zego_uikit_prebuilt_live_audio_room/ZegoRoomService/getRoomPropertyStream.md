


# getRoomPropertyStream method








Stream&lt;[RoomProperty](../../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)> getRoomPropertyStream
()





<p>only notify the property which changed
you can get full properties by getRoomProperties() function</p>



## Implementation

```dart
Stream<RoomProperty> getRoomPropertyStream() {
  return ZegoUIKitCore.shared.coreData.room.propertyUpdateStream.stream;
}
```







