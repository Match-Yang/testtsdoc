


# ZegoAcceptInvitationButton constructor






const
ZegoAcceptInvitationButton({Key? key, required String inviterID, String? text, TextStyle? textStyle, [ButtonIcon](../../zego_uikit_prebuilt_live_audio_room/ButtonIcon-class.md)? icon, Size? iconSize, Size? buttonSize, double? iconTextSpacing, bool verticalLayout = true, void onPressed(String code, String message)?, Color? clickableTextColor = Colors.black, Color? unclickableTextColor = Colors.black, Color? clickableBackgroundColor = Colors.transparent, Color? unclickableBackgroundColor = Colors.transparent})





## Implementation

```dart
const ZegoAcceptInvitationButton({
  Key? key,
  required this.inviterID,
  this.text,
  this.textStyle,
  this.icon,
  this.iconSize,
  this.buttonSize,
  this.iconTextSpacing,
  this.verticalLayout = true,
  this.onPressed,
  this.clickableTextColor = Colors.black,
  this.unclickableTextColor = Colors.black,
  this.clickableBackgroundColor = Colors.transparent,
  this.unclickableBackgroundColor = Colors.transparent,
}) : super(key: key);
```







