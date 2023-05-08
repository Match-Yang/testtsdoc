


# quit method








void quit
()








## Implementation

```dart
void quit() {
  ZegoUIKit().leaveRoom().then((result) {
    ZegoLoggerService.logInfo(
      'leave room result, ${result.errorCode} ${result.extendedData}',
      tag: 'uikit',
      subTag: 'leave button',
    );
  });

  if (onPress != null) {
    onPress!();
  }
}
```







