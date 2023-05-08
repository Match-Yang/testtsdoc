


# ZIMImageMessage constructor







ZIMImageMessage(String fileLocalPath)





## Implementation

```dart
ZIMImageMessage(String fileLocalPath) : super(fileLocalPath: fileLocalPath) {
  super.type = ZIMMessageType.image;
}
```







