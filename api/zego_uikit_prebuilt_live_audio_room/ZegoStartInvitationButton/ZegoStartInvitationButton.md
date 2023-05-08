


# ZegoStartInvitationButton constructor






const
ZegoStartInvitationButton({Key? key, required int invitationType, required List&lt;String> invitees, required String data, [ZegoNotificationConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoNotificationConfig-class.md)? notificationConfig, int timeoutSeconds = 60, String? text, TextStyle? textStyle, [ButtonIcon](../../zego_uikit_prebuilt_live_audio_room/ButtonIcon-class.md)? icon, Size? iconSize, double? iconTextSpacing, bool verticalLayout = true, Size? buttonSize, bool onWillPressed()?, void onPressed(String code, String message, String invitationID, List&lt;String> errorUsers)?, Color? clickableTextColor = Colors.black, Color? unclickableTextColor = Colors.black, Color? clickableBackgroundColor = Colors.transparent, Color? unclickableBackgroundColor = Colors.transparent})





## Implementation

```dart
const ZegoStartInvitationButton({
  Key? key,
  required this.invitationType,
  required this.invitees,
  required this.data,
  this.notificationConfig,
  this.timeoutSeconds = 60,
  this.text,
  this.textStyle,
  this.icon,
  this.iconSize,
  this.iconTextSpacing,
  this.verticalLayout = true,
  this.buttonSize,
  this.onWillPressed,
  this.onPressed,
  this.clickableTextColor = Colors.black,
  this.unclickableTextColor = Colors.black,
  this.clickableBackgroundColor = Colors.transparent,
  this.unclickableBackgroundColor = Colors.transparent,
}) : super(key: key);
```







