


# getSoundLevelStream method








Stream&lt;double> getSoundLevelStream
(String userID)





<p>get sound level notifier</p>



## Implementation

```dart
Stream<double> getSoundLevelStream(String userID) {
  return ZegoUIKitCore.shared.coreData.getUser(userID).soundLevel.stream;
}
```







