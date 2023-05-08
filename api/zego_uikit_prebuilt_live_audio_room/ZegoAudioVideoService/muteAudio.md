


# muteAudio method








Future&lt;void> muteAudio
(String userID, bool mute)








## Implementation

```dart
Future<void> muteAudio(String userID, bool mute) async {
  return ZegoUIKitCore.shared.muteAudio(userID, mute);
}
```







