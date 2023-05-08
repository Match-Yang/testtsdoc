


# initLog method








Future&lt;void> initLog
({String folderName = 'zego_prebuilt'})








## Implementation

```dart
Future<void> initLog({String folderName = 'zego_prebuilt'}) async {
  return FlutterLogs.initLogs(
          logLevelsEnabled: [
            LogLevel.INFO,
            LogLevel.WARNING,
            LogLevel.ERROR,
            LogLevel.SEVERE
          ],
          timeStampFormat: TimeStampFormat.TIME_FORMAT_24_FULL,
          directoryStructure: DirectoryStructure.SINGLE_FILE_FOR_DAY,
          logTypesEnabled: ['device', 'network', 'errors'],
          logFileExtension: LogFileExtension.LOG,
          logsWriteDirectoryName: folderName,
          logsExportDirectoryName: '$folderName/Exported',
          debugFileOperations: true,
          isDebuggable: true)
      .then((value) {
    isZegoLoggerInit = true;

    FlutterLogs.setDebugLevel(0);
    FlutterLogs.logInfo(
      'log',
      'init',
      '==========================================$value',
    );
  });
}
```







