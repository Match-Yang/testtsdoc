


# getMixAudioVideoCameraStateNotifier method








ValueNotifier&lt;bool> getMixAudioVideoCameraStateNotifier
(String mixerID, String userID)








## Implementation

```dart
ValueNotifier<bool> getMixAudioVideoCameraStateNotifier(
    String mixerID, String userID) {
  return ZegoUIKitCore.shared.coreData.mixerStreamDic[mixerID]?.users
          .firstWhere((user) => user.id == userID,
              orElse: ZegoUIKitCoreUser.empty)
          .camera ??
      ValueNotifier(false);
}
```







