


# getScreenSharingStateNotifier method








ValueNotifier&lt;bool> getScreenSharingStateNotifier
()





<p>get screen share notifier</p>



## Implementation

```dart
ValueNotifier<bool> getScreenSharingStateNotifier() {
  return ZegoUIKitCore.shared.coreData.isScreenSharing;
}
```







