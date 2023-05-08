


# startPlayAnotherRoomAudioVideo method








Future&lt;void> startPlayAnotherRoomAudioVideo
(String roomID, String userID, {String userName = ''})








## Implementation

```dart
Future<void> startPlayAnotherRoomAudioVideo(String roomID, String userID,
    {String userName = ''}) async {
  return ZegoUIKitCore.shared
      .startPlayAnotherRoomAudioVideo(roomID, userID, userName);
}
```







