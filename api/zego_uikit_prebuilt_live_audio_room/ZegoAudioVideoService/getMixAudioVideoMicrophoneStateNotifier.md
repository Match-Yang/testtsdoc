


# getMixAudioVideoMicrophoneStateNotifier method








ValueNotifier&lt;bool> getMixAudioVideoMicrophoneStateNotifier
(String mixerID, String userID)








## Implementation

```dart
ValueNotifier<bool> getMixAudioVideoMicrophoneStateNotifier(
    String mixerID, String userID) {
  return ZegoUIKitCore.shared.coreData.mixerStreamDic[mixerID]?.users
          .firstWhere((user) => user.id == userID,
              orElse: ZegoUIKitCoreUser.empty)
          .microphone ??
      ValueNotifier(false);
}
```







