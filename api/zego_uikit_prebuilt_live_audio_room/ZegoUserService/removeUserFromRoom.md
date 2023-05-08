


# removeUserFromRoom method








Future&lt;bool> removeUserFromRoom
(List&lt;String> userIDs)





<p>remove user from room, kick out</p>



## Implementation

```dart
Future<bool> removeUserFromRoom(List<String> userIDs) async {
  return ZegoUIKitCore.shared.removeUserFromRoom(userIDs);
}
```







