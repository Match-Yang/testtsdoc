


# getUserLeaveStream method








Stream&lt;List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>> getUserLeaveStream
()





<p>get user leave notifier</p>



## Implementation

```dart
Stream<List<ZegoUIKitUser>> getUserLeaveStream() {
  return ZegoUIKitCore.shared.coreData.userLeaveStreamCtrl.stream
      .map((users) => users.map((e) => e.toZegoUikitUser()).toList());
}
```







