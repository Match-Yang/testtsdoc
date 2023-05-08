


# getMicrophoneStateNotifier method








ValueNotifier&lt;bool> getMicrophoneStateNotifier
(String userID)





<p>get microphone state notifier</p>



## Implementation

```dart
ValueNotifier<bool> getMicrophoneStateNotifier(String userID) {
  return ZegoUIKitCore.shared.coreData.getUser(userID).microphone;
}
```







