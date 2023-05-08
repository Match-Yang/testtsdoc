


# ZIMVideoMessage constructor







ZIMVideoMessage(String fileLocalPath)





## Implementation

```dart
ZIMVideoMessage(String fileLocalPath) : super(fileLocalPath: fileLocalPath) {
  super.type = ZIMMessageType.video;
}
```







