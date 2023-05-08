


# getUserJoinStream method








Stream&lt;List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>> getUserJoinStream
()





<p>get user join notifier</p>



## Implementation

```dart
Stream<List<ZegoUIKitUser>> getUserJoinStream() {
  return ZegoUIKitCore.shared.coreData.userJoinStreamCtrl.stream
      .map((users) => users.map((e) => e.toZegoUikitUser()).toList());
}
```







