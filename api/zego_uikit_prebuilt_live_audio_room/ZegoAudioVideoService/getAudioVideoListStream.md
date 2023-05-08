


# getAudioVideoListStream method








Stream&lt;List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>> getAudioVideoListStream
()








## Implementation

```dart
Stream<List<ZegoUIKitUser>> getAudioVideoListStream() {
  return ZegoUIKitCore.shared.coreData.audioVideoListStreamCtrl.stream
      .map((users) => users.map((e) => e.toZegoUikitUser()).toList());
}
```







