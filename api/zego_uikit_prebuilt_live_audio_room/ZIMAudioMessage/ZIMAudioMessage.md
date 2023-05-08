


# ZIMAudioMessage constructor







ZIMAudioMessage(String fileLocalPath)





## Implementation

```dart
ZIMAudioMessage(String fileLocalPath) : super(fileLocalPath: fileLocalPath) {
  super.type = ZIMMessageType.audio;
}
```







