


# text property









String text
  







## Implementation

```dart
String get text {
  final mapValues = {
    RoomPropertyKey.host: 'host',
    RoomPropertyKey.liveStatus: 'live_status',
  };

  return mapValues[this]!;
}
```








