


# setRoomProperty method








Future&lt;bool> setRoomProperty
(String key, String value)





<p>update one room property</p>



## Implementation

```dart
Future<bool> setRoomProperty(String key, String value) async {
  return ZegoUIKitCore.shared.setRoomProperty(key, value);
}
```







