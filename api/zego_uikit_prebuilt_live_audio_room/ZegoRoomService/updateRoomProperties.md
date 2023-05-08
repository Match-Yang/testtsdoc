


# updateRoomProperties method








Future&lt;bool> updateRoomProperties
(Map&lt;String, String> properties)





<p>update room properties</p>



## Implementation

```dart
Future<bool> updateRoomProperties(Map<String, String> properties) async {
  return ZegoUIKitCore.shared
      .updateRoomProperties(Map<String, String>.from(properties));
}
```







