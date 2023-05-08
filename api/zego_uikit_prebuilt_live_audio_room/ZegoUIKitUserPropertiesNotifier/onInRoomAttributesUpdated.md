


# onInRoomAttributesUpdated method








void onInRoomAttributesUpdated
()








## Implementation

```dart
void onInRoomAttributesUpdated() {
  _updateTimestamp = DateTime.now().microsecondsSinceEpoch;

  notifyListeners();
}
```







