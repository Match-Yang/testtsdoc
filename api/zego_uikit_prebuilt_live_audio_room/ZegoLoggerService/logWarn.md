


# logWarn method








Future&lt;void> logWarn
(String logMessage, {String tag = '', String subTag = ''})








## Implementation

```dart
static Future<void> logWarn(
  String logMessage, {
  String tag = '',
  String subTag = '',
}) async {
  if (!isZegoLoggerInit) {
    debugPrint(
        '[WARN] ${DateTime.now().toString()} [$tag] [$subTag] $logMessage');
    return;
  }

  return FlutterLogs.logWarn(tag, subTag, logMessage);
}
```







