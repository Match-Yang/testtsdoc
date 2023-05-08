


# startPlayMixAudioVideo method








Future&lt;void> startPlayMixAudioVideo
(String mixerID, List&lt;String> users)








## Implementation

```dart
Future<void> startPlayMixAudioVideo(
    String mixerID, List<String> users) async {
  return ZegoUIKitCore.shared.startPlayMixAudioVideo(mixerID, users);
}
```







