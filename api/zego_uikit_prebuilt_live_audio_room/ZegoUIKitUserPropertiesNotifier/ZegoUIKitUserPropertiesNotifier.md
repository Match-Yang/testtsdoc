


# ZegoUIKitUserPropertiesNotifier constructor







ZegoUIKitUserPropertiesNotifier([ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) user)





## Implementation

```dart
ZegoUIKitUserPropertiesNotifier(ZegoUIKitUser user) : _user = user {
  _coreUser = ZegoUIKitCore.shared.coreData.getUser(_user.id);
  listenUserProperty();
}
```







