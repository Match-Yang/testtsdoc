


# setUsersInRoomAttributes method








Future&lt;[ZegoSignalingPluginSetUsersInRoomAttributesResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetUsersInRoomAttributesResult-class.md)> setUsersInRoomAttributes
({required String roomID, required List&lt;String> userIDs, required Map&lt;String, String> setAttributes, bool isDeleteAfterOwnerLeft = true})





<p>set users in room attributes</p>



## Implementation

```dart
Future<ZegoSignalingPluginSetUsersInRoomAttributesResult>
    setUsersInRoomAttributes({
  required String roomID,
  required List<String> userIDs,
  required Map<String, String> setAttributes,
  bool isDeleteAfterOwnerLeft = true,
});
```







