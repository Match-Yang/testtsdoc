


# ZegoCameraStateIcon constructor







ZegoCameraStateIcon({Key? key, required [ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)? targetUser, Image? iconCameraOn, Image? iconCameraOff})





## Implementation

```dart
ZegoCameraStateIcon({
  Key? key,
  required this.targetUser,
  this.iconCameraOn,
  this.iconCameraOff,
}) : super(
        key: key,
        notifier: ZegoUIKit().getCameraStateNotifier(targetUser?.id ?? ''),
        normalIcon: iconCameraOff ??
            UIKitImage.asset(StyleIconUrls.iconVideoViewCameraOff),
        checkedIcon: iconCameraOn ??
            UIKitImage.asset(StyleIconUrls.iconVideoViewCameraOn),
      );
```







