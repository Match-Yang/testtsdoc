


# endRoomPropertiesBatchOperation method








Future&lt;[ZegoSignalingPluginEndRoomBatchOperationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEndRoomBatchOperationResult-class.md)> endRoomPropertiesBatchOperation
({required String roomID})

_<span class="feature">inherited</span>_



<p>end room properties in batch operation</p>



## Implementation

```dart
Future<ZegoSignalingPluginEndRoomBatchOperationResult>
    endRoomPropertiesBatchOperation({
  required String roomID,
}) async {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .endRoomPropertiesBatchOperation(roomID: roomID);
}
```







