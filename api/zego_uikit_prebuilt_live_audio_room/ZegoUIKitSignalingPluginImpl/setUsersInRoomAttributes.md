


# setUsersInRoomAttributes method








Future&lt;[ZegoSignalingPluginSetUsersInRoomAttributesResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetUsersInRoomAttributesResult-class.md)> setUsersInRoomAttributes
({required String roomID, required String key, required String value, required List&lt;String> userIDs})

_<span class="feature">inherited</span>_



<p>set users in-room attributes</p>



## Implementation

```dart
Future<ZegoSignalingPluginSetUsersInRoomAttributesResult>
    setUsersInRoomAttributes(
        {required String roomID,
        required String key,
        required String value,
        required List<String> userIDs}) async {
  return ZegoPluginAdapter().signalingPlugin!.setUsersInRoomAttributes(
        roomID: roomID,
        setAttributes: {key: value},
        userIDs: userIDs,
      );
}
```







