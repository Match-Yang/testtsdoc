


# onCameraStatusChanged method








void onCameraStatusChanged
()








## Implementation

```dart
void onCameraStatusChanged() {
  _updateTimestamp = DateTime.now().microsecondsSinceEpoch;

  notifyListeners();
}
```







