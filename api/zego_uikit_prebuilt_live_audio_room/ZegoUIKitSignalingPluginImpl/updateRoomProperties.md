


# updateRoomProperties method








Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)> updateRoomProperties
({required String roomID, required Map&lt;String, String> roomProperties, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false})

_<span class="feature">inherited</span>_






## Implementation

```dart
Future<ZegoSignalingPluginRoomPropertiesOperationResult>
    updateRoomProperties({
  required String roomID,
  required Map<String, String> roomProperties,
  bool isForce = false,
  bool isDeleteAfterOwnerLeft = false,
  bool isUpdateOwner = false,
}) async {
  return ZegoPluginAdapter().signalingPlugin!.updateRoomProperties(
        roomID: roomID,
        isForce: isForce,
        isDeleteAfterOwnerLeft: isDeleteAfterOwnerLeft,
        isUpdateOwner: isUpdateOwner,
        roomProperties: roomProperties,
      );
}
```







