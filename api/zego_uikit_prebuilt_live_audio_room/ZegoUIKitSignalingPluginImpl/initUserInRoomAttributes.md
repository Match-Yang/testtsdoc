


# initUserInRoomAttributes method








void initUserInRoomAttributes
()

_<span class="feature">inherited</span>_






## Implementation

```dart
void initUserInRoomAttributes() {
  ZegoLoggerService.logInfo(
    'user in-room init',
    tag: 'uikit',
    subTag: 'user attributes',
  );
  _private.init();
}
```







