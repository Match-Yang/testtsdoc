


# getUseFrontFacingCameraStateNotifier method








ValueNotifier&lt;bool> getUseFrontFacingCameraStateNotifier
(String userID)





<p>get front facing camera switch notifier</p>



## Implementation

```dart
ValueNotifier<bool> getUseFrontFacingCameraStateNotifier(String userID) {
  return ZegoUIKitCore.shared.coreData.getUser(userID).isFrontFacing;
}
```







