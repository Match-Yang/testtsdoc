


# getInRoomMessages method








List&lt;[ZegoInRoomMessage](../../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md)> getInRoomMessages
()





<p>get in-room messages</p>



## Implementation

```dart
List<ZegoInRoomMessage> getInRoomMessages() {
  return ZegoUIKitCore.shared.coreMessage.messageList;
}
```







