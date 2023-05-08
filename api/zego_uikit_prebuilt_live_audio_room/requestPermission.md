


# requestPermission function










Future&lt;bool> requestPermission
([Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md) permission)








## Implementation

```dart
Future<bool> requestPermission(Permission permission) async {
  final status = await permission.request();
  if (status != PermissionStatus.granted) {
    ZegoLoggerService.logInfo(
      'Error: $permission permission not granted, $status',
      tag: 'uikit',
      subTag: 'permission',
    );
    return false;
  }

  return true;
}
```







