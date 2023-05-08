


# getScreenSharingList method








List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> getScreenSharingList
()





<p>get screen sharing list</p>



## Implementation

```dart
List<ZegoUIKitUser> getScreenSharingList() {
  return ZegoUIKitCore.shared.coreData
      .getAudioVideoList(streamType: ZegoStreamType.screenSharing)
      .map((e) => e.toZegoUikitUser())
      .toList();
}
```







