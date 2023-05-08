


# ZegoLayout.gallery constructor







ZegoLayout.gallery({bool addBorderRadiusAndSpacingBetweenView = true, bool showNewScreenSharingViewInFullscreenMode = true, [ZegoShowFullscreenModeToggleButtonRules](../../zego_uikit_prebuilt_live_audio_room/ZegoShowFullscreenModeToggleButtonRules.md) showScreenSharingFullscreenModeToggleButtonRules = ZegoShowFullscreenModeToggleButtonRules.showWhenScreenPressed})





## Implementation

```dart
factory ZegoLayout.gallery(
    {
    /// whether to display rounded corners and spacing between views
    bool addBorderRadiusAndSpacingBetweenView = true,
    bool showNewScreenSharingViewInFullscreenMode = true,
    ZegoShowFullscreenModeToggleButtonRules showScreenSharingFullscreenModeToggleButtonRules =
        ZegoShowFullscreenModeToggleButtonRules.showWhenScreenPressed}) {
  return ZegoLayoutGalleryConfig(
      addBorderRadiusAndSpacingBetweenView:
          addBorderRadiusAndSpacingBetweenView,
      showNewScreenSharingViewInFullscreenMode:
          showNewScreenSharingViewInFullscreenMode,
      showScreenSharingFullscreenModeToggleButtonRules:
          showScreenSharingFullscreenModeToggleButtonRules);
}
```







