


# ZIMCommandMessage constructor







ZIMCommandMessage({required Uint8List message})





## Implementation

```dart
ZIMCommandMessage({
  required this.message,
}) {
  super.type = ZIMMessageType.command;
}
```







