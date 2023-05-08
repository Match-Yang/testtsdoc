


# getInRoomMessageListStream method








Stream&lt;List&lt;[ZegoInRoomMessage](../../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md)>> getInRoomMessageListStream
()





<p>get in-room messages notifier</p>



## Implementation

```dart
Stream<List<ZegoInRoomMessage>> getInRoomMessageListStream() {
  return ZegoUIKitCore.shared.coreMessage.streamControllerMessageList.stream;
}
```







