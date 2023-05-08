


# ZegoInRoomMessage.fromBroadcastMessage constructor







ZegoInRoomMessage.fromBroadcastMessage([ZegoBroadcastMessageInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoBroadcastMessageInfo-class.md) message)





## Implementation

```dart
ZegoInRoomMessage.fromBroadcastMessage(ZegoBroadcastMessageInfo message)
    : this(
        user: ZegoUIKitUser.fromZego(message.fromUser),
        message: message.message,
        timestamp: message.sendTime,
        messageID: message.messageID,
      );
```







