


# getRoomPropertiesStream method








Stream&lt;Map&lt;String, [RoomProperty](../../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)>> getRoomPropertiesStream
()





<p>only notify the properties which changed
you can get full properties by getRoomProperties() function</p>



## Implementation

```dart
Stream<Map<String, RoomProperty>> getRoomPropertiesStream() {
  return ZegoUIKitCore.shared.coreData.room.propertiesUpdatedStream.stream;
}
```







