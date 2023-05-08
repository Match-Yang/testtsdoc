


# sendInRoomCommand method








Future&lt;bool> sendInRoomCommand
(String command, List&lt;String> toUserIDs)





<p><code>toUserIDs</code> send to everyone if empty</p>



## Implementation

```dart
Future<bool> sendInRoomCommand(
  String command,
  List<String> toUserIDs,
) async {
  return ZegoUIKitCore.shared.sendInRoomCommand(command, toUserIDs);
}
```







