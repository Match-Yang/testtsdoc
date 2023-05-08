


# getInRoomMessageStream method








Stream&lt;[ZegoInRoomMessage](../../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md)> getInRoomMessageStream
()





<p>get in-room messages one-by-one notifier</p>



## Implementation

```dart
Stream<ZegoInRoomMessage> getInRoomMessageStream() {
  return ZegoUIKitCore.shared.coreMessage.streamControllerMessage.stream;
}
```







