


# ZegoMoreButton constructor






const
ZegoMoreButton({Key? key, required List&lt;Widget> menuButtonListFunc(), [ButtonIcon](../../zego_uikit_prebuilt_live_audio_room/ButtonIcon-class.md)? icon, Size menuItemSize = const Size(60.0, 60.0), int menuItemCountPerRow = 5, double menuRowHeight = 80.0, Color menuBackgroundColor = const Color(0xff262A2D), Size? iconSize, Size? buttonSize, dynamic onSheetPopUp(int)?, dynamic onSheetPop(int)?})





## Implementation

```dart
const ZegoMoreButton({
  Key? key,
  required this.menuButtonListFunc,
  this.icon,
  this.menuItemSize = const Size(60.0, 60.0),
  this.menuItemCountPerRow = 5,
  this.menuRowHeight = 80.0,
  this.menuBackgroundColor = const Color(0xff262A2D),
  this.iconSize,
  this.buttonSize,
  this.onSheetPopUp,
  this.onSheetPop,
}) : super(key: key);
```







