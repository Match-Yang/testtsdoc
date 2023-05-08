


# onMicrophoneStatusChanged method








void onMicrophoneStatusChanged
()








## Implementation

```dart
void onMicrophoneStatusChanged() {
  _updateTimestamp = DateTime.now().microsecondsSinceEpoch;

  notifyListeners();
}
```







