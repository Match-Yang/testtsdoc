


# updateRoomProperty method








Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)> updateRoomProperty
({required String roomID, required String key, required String value, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false})

_<span class="feature">inherited</span>_



<p>update room property</p>



## Implementation

```dart
Future<ZegoSignalingPluginRoomPropertiesOperationResult> updateRoomProperty({
  required String roomID,
  required String key,
  required String value,
  bool isForce = false,
  bool isDeleteAfterOwnerLeft = false,
  bool isUpdateOwner = false,
}) async {
  return ZegoPluginAdapter().signalingPlugin!.updateRoomProperties(
    roomID: roomID,
    isForce: isForce,
    isDeleteAfterOwnerLeft: isDeleteAfterOwnerLeft,
    isUpdateOwner: isUpdateOwner,
    roomProperties: {key: value},
  );
}
```







