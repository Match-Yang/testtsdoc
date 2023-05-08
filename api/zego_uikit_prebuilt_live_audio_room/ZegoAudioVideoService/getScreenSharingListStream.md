


# getScreenSharingListStream method








Stream&lt;List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>> getScreenSharingListStream
()








## Implementation

```dart
Stream<List<ZegoUIKitUser>> getScreenSharingListStream() {
  return ZegoUIKitCore.shared.coreData.screenSharingListStreamCtrl.stream
      .map((users) => users.map((e) => e.toZegoUikitUser()).toList());
}
```







