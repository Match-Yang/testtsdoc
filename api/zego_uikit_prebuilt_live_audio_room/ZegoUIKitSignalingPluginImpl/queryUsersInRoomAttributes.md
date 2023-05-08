


# queryUsersInRoomAttributes method








Future&lt;[ZegoSignalingPluginQueryUsersInRoomAttributesResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryUsersInRoomAttributesResult-class.md)> queryUsersInRoomAttributes
({required String roomID, String nextFlag = '', int count = 100})

_<span class="feature">inherited</span>_



<p>query user in-room attributes</p>



## Implementation

```dart
Future<ZegoSignalingPluginQueryUsersInRoomAttributesResult>
    queryUsersInRoomAttributes({
  required String roomID,
  String nextFlag = '',
  int count = 100,
}) async {
  final result =
      await ZegoPluginAdapter().signalingPlugin!.queryUsersInRoomAttributes(
            roomID: roomID,
            nextFlag: nextFlag,
            count: count,
          );

  if (result.error == null) {
    _private.updateUserInRoomAttributes(result.attributes);
  }

  return result;
}
```







