


# logErrorTrace method








Future&lt;void> logErrorTrace
(String logMessage, Error e, {String tag = '', String subTag = ''})








## Implementation

```dart
static Future<void> logErrorTrace(
  String logMessage,
  Error e, {
  String tag = '',
  String subTag = '',
}) async {
  if (!isZegoLoggerInit) {
    debugPrint(
        '[ERROR] ${DateTime.now().toString()} [$tag] [$subTag] $logMessage');
    return;
  }

  return FlutterLogs.logErrorTrace(tag, subTag, logMessage, e);
}
```







