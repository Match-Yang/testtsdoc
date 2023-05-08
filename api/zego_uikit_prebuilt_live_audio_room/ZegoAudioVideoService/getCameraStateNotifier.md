


# getCameraStateNotifier method








ValueNotifier&lt;bool> getCameraStateNotifier
(String userID)





<p>get camera state notifier</p>



## Implementation

```dart
ValueNotifier<bool> getCameraStateNotifier(String userID) {
  return ZegoUIKitCore.shared.coreData.getUser(userID).camera;
}
```







