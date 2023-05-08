


# showScreenSharingViewInFullscreenMode method








void showScreenSharingViewInFullscreenMode
(String userID, bool isFullscreen)








## Implementation

```dart
void showScreenSharingViewInFullscreenMode(String userID, bool isFullscreen) {
  _fullscreenUserNotifier.value =
      isFullscreen ? ZegoUIKit().getUser(userID) : null;
}
```







