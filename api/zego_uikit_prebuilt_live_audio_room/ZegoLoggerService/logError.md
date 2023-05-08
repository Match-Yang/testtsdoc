


# logError method








Future&lt;void> logError
(String logMessage, {String tag = '', String subTag = ''})








## Implementation

```dart
static Future<void> logError(
  String logMessage, {
  String tag = '',
  String subTag = '',
}) async {
  if (!isZegoLoggerInit) {
    debugPrint(
        '[ERROR] ${DateTime.now().toString()} [$tag] [$subTag] $logMessage');
    return;
  }

  return FlutterLogs.logError(tag, subTag, logMessage);
}
```







