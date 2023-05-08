


# getUser method








[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) getUser
(String userID)





<p>get user by user id</p>



## Implementation

```dart
ZegoUIKitUser getUser(String userID) {
  return ZegoUIKitCore.shared.coreData.getUser(userID).toZegoUikitUser();
}
```







