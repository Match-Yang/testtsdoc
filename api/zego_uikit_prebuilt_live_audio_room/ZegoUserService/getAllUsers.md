


# getAllUsers method








List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> getAllUsers
()





<p>get all users, include local user and remote users</p>



## Implementation

```dart
List<ZegoUIKitUser> getAllUsers() {
  return [
    ZegoUIKitCore.shared.coreData.localUser,
    ...ZegoUIKitCore.shared.coreData.remoteUsersList
  ]
      .where((user) => !user.isAnotherRoomUser)
      .map((user) => user.toZegoUikitUser())
      .toList();
}
```







