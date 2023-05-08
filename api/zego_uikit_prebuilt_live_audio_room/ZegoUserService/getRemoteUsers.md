


# getRemoteUsers method








List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> getRemoteUsers
()





<p>get remote users, not include local user</p>



## Implementation

```dart
List<ZegoUIKitUser> getRemoteUsers() {
  return ZegoUIKitCore.shared.coreData.remoteUsersList
      .where((user) => !user.isAnotherRoomUser)
      .map((user) => user.toZegoUikitUser())
      .toList();
}
```







