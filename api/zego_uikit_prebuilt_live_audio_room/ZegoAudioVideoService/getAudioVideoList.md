


# getAudioVideoList method








List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> getAudioVideoList
()





<p>get audio video list</p>



## Implementation

```dart
List<ZegoUIKitUser> getAudioVideoList() {
  return ZegoUIKitCore.shared.coreData
      .getAudioVideoList()
      .map((e) => e.toZegoUikitUser())
      .toList();
}
```







