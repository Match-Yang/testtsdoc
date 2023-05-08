


# endRoomPropertiesBatchOperation method







- @override

Future&lt;[ZegoSignalingPluginEndRoomBatchOperationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEndRoomBatchOperationResult-class.md)> endRoomPropertiesBatchOperation
({required String roomID})

_<span class="feature">override</span>_



<p>end room properties batch operation</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginEndRoomBatchOperationResult>
    endRoomPropertiesBatchOperation({
  required String roomID,
}) async {
  return ZIM
      .getInstance()!
      .endRoomAttributesBatchOperation(roomID)
      .then((value) => const ZegoSignalingPluginEndRoomBatchOperationResult())
      .catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'end room properties batch operation, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginEndRoomBatchOperationResult(
      error: error,
    );
  });
}
```







