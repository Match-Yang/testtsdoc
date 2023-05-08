


# getLocalUser method








[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) getLocalUser
()





<p>get local user</p>



## Implementation

```dart
ZegoUIKitUser getLocalUser() {
  return ZegoUIKitCore.shared.coreData.localUser.toZegoUikitUser();
}
```







