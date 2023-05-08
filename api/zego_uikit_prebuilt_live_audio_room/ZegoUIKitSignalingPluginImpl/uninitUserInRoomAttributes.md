


# uninitUserInRoomAttributes method








void uninitUserInRoomAttributes
()

_<span class="feature">inherited</span>_






## Implementation

```dart
void uninitUserInRoomAttributes() {
  ZegoLoggerService.logInfo(
    'user in-room uninit',
    tag: 'uikit',
    subTag: 'user attributes',
  );
  _private.uninit();
}
```







