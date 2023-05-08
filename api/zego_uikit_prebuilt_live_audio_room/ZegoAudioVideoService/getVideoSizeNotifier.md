


# getVideoSizeNotifier method








ValueNotifier&lt;Size> getVideoSizeNotifier
(String userID)





<p>get video size notifier</p>



## Implementation

```dart
ValueNotifier<Size> getVideoSizeNotifier(String userID) {
  return ZegoUIKitCore.shared.coreData.getUser(userID).viewSize;
}
```







