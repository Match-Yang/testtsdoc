


# ZegoLayout.pictureInPicture constructor







ZegoLayout.pictureInPicture({bool isSmallViewDraggable = true, bool switchLargeOrSmallViewByClick = true, [ZegoViewPosition](../../zego_uikit_prebuilt_live_audio_room/ZegoViewPosition.md) smallViewPosition = ZegoViewPosition.topRight, EdgeInsets? smallViewMargin, Size? smallViewSize, EdgeInsets? spacingBetweenSmallViews, bool showNewScreenSharingViewInFullscreenMode = true, [ZegoShowFullscreenModeToggleButtonRules](../../zego_uikit_prebuilt_live_audio_room/ZegoShowFullscreenModeToggleButtonRules.md) showScreenSharingFullscreenModeToggleButtonRules = ZegoShowFullscreenModeToggleButtonRules.showWhenScreenPressed})





## Implementation

```dart
factory ZegoLayout.pictureInPicture({
  /// small video view is draggable if set true
  bool isSmallViewDraggable = true,

  ///  Whether you can switch view's position by clicking on the small view
  bool switchLargeOrSmallViewByClick = true,

  /// whether to hide the local View when the local camera is closed
  ZegoViewPosition smallViewPosition = ZegoViewPosition.topRight,
  EdgeInsets? smallViewMargin,

  ///
  Size? smallViewSize,

  ///
  EdgeInsets? spacingBetweenSmallViews,
  bool showNewScreenSharingViewInFullscreenMode = true,
  ZegoShowFullscreenModeToggleButtonRules showScreenSharingFullscreenModeToggleButtonRules =
      ZegoShowFullscreenModeToggleButtonRules.showWhenScreenPressed,
}) {
  return ZegoLayoutPictureInPictureConfig(
      isSmallViewDraggable: isSmallViewDraggable,
      switchLargeOrSmallViewByClick: switchLargeOrSmallViewByClick,
      smallViewPosition: smallViewPosition,
      smallViewSize: smallViewSize,
      smallViewMargin: smallViewMargin,
      spacingBetweenSmallViews: spacingBetweenSmallViews,
      showNewScreenSharingViewInFullscreenMode:
          showNewScreenSharingViewInFullscreenMode,
      showScreenSharingFullscreenModeToggleButtonRules:
          showScreenSharingFullscreenModeToggleButtonRules);
}
```







