


# ZegoScreenSharingView constructor






const
ZegoScreenSharingView({Key? key, required [ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)? user, [ZegoAudioVideoViewForegroundBuilder](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoViewForegroundBuilder.md)? foregroundBuilder, [ZegoAudioVideoViewBackgroundBuilder](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoViewBackgroundBuilder.md)? backgroundBuilder, double? borderRadius, Color borderColor = const Color(0xffA4A4A4), Map&lt;String, dynamic> extraInfo = const {}, [ZegoShowFullscreenModeToggleButtonRules](../../zego_uikit_prebuilt_live_audio_room/ZegoShowFullscreenModeToggleButtonRules.md) showFullscreenModeToggleButtonRules = ZegoShowFullscreenModeToggleButtonRules.showWhenScreenPressed, [ZegoScreenSharingViewController](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenSharingViewController-class.md)? controller})





## Implementation

```dart
const ZegoScreenSharingView({
  Key? key,
  required this.user,
  this.foregroundBuilder,
  this.backgroundBuilder,
  this.borderRadius,
  this.borderColor = const Color(0xffA4A4A4),
  this.extraInfo = const {},
  this.showFullscreenModeToggleButtonRules =
      ZegoShowFullscreenModeToggleButtonRules.showWhenScreenPressed,
  this.controller,
}) : super(key: key);
```







