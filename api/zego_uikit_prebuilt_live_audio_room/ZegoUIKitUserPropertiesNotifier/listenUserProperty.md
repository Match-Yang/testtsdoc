


# listenUserProperty method








void listenUserProperty
()








## Implementation

```dart
void listenUserProperty() {
  _coreUser.camera.addListener(onCameraStatusChanged);
  _coreUser.microphone.addListener(onMicrophoneStatusChanged);
  _coreUser.inRoomAttributes.addListener(onInRoomAttributesUpdated);
}
```







