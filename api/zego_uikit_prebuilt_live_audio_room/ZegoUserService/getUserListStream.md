


# getUserListStream method








Stream&lt;List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>> getUserListStream
()





<p>get user list notifier</p>



## Implementation

```dart
Stream<List<ZegoUIKitUser>> getUserListStream() {
  return ZegoUIKitCore.shared.coreData.userListStreamCtrl.stream.map(
      (users) => users
          .where((user) => !user.isAnotherRoomUser)
          .map((e) => e.toZegoUikitUser())
          .toList());
}
```







