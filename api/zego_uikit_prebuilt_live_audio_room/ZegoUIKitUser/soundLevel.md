


# soundLevel property









Stream&lt;double> soundLevel
  







## Implementation

```dart
Stream<double> get soundLevel {
  return ZegoUIKitCore.shared.coreData.getUser(id).soundLevel.stream;
}
```








