


# sendInRoomMessage method








void sendInRoomMessage
(String message)





<p>send in-room message</p>



## Implementation

```dart
void sendInRoomMessage(String message) {
  return ZegoUIKitCore.shared.coreMessage.sendBroadcastMessage(message);
}
```







