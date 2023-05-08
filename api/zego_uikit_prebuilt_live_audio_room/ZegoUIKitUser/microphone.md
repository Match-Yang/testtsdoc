


# microphone property









ValueNotifier&lt;bool> microphone
  







## Implementation

```dart
ValueNotifier<bool> get microphone {
  return ZegoUIKitCore.shared.coreData.getUser(id).microphone;
}
```








