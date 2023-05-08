


# getAudioVideoViewNotifier method








ValueNotifier&lt;Widget?> getAudioVideoViewNotifier
(String? userID, {bool isMainStream = true})





<p>get audio video view notifier</p>



## Implementation

```dart
ValueNotifier<Widget?> getAudioVideoViewNotifier(
  String? userID, {
  bool isMainStream = true,
}) {
  if (userID == null ||
      userID == ZegoUIKitCore.shared.coreData.localUser.id) {
    return isMainStream
        ? ZegoUIKitCore.shared.coreData.localUser.view
        : ZegoUIKitCore.shared.coreData.localUser.auxView;
  } else {
    final targetUser = ZegoUIKitCore.shared.coreData.remoteUsersList
        .firstWhere((user) => user.id == userID,
            orElse: ZegoUIKitCoreUser.empty);
    return isMainStream ? targetUser.view : targetUser.auxView;
  }
}
```







