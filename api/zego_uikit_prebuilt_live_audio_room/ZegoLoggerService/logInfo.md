


# logInfo method








Future&lt;void> logInfo
(String logMessage, {String tag = '', String subTag = ''})








## Implementation

```dart
static Future<void> logInfo(
  String logMessage, {
  String tag = '',
  String subTag = '',
}) async {
  if (!isZegoLoggerInit) {
    debugPrint(
        '[INFO] ${DateTime.now().toString()} [$tag] [$subTag] $logMessage');
    return;
  }

  return FlutterLogs.logInfo(tag, subTag, logMessage);
}
```







