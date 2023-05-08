


# ZIMFileMessage constructor







ZIMFileMessage(String fileLocalPath)





## Implementation

```dart
ZIMFileMessage(String fileLocalPath) : super(fileLocalPath: fileLocalPath) {
  super.type = ZIMMessageType.file;
}
```







