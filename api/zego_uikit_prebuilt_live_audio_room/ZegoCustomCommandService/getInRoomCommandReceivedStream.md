


# getInRoomCommandReceivedStream method








Stream&lt;[ZegoInRoomCommandReceivedData](../../zego_uikit_prebuilt_live_audio_room/ZegoInRoomCommandReceivedData-class.md)> getInRoomCommandReceivedStream
()





<p>get in-room command received notifier</p>



## Implementation

```dart
Stream<ZegoInRoomCommandReceivedData> getInRoomCommandReceivedStream() {
  return ZegoUIKitCore.shared.coreData.customCommandReceivedStreamCtrl.stream;
}
```







