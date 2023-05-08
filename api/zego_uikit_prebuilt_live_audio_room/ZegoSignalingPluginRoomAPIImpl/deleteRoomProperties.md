


# deleteRoomProperties method







- @override

Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)> deleteRoomProperties
({required String roomID, required List&lt;String> keys, required bool isForce})

_<span class="feature">override</span>_



<p>delete room properties</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginRoomPropertiesOperationResult>
    deleteRoomProperties({
  required String roomID,
  required List<String> keys,
  required bool isForce,
}) async {
  return ZIM
      .getInstance()!
      .deleteRoomAttributes(
        keys,
        roomID,
        ZIMRoomAttributesDeleteConfig()..isForce = isForce,
      )
      .then((zimResult) {
    return ZegoSignalingPluginRoomPropertiesOperationResult(
      errorKeys: zimResult.errorKeys,
    );
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'delete room properties, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginRoomPropertiesOperationResult(
      error: error,
      errorKeys: keys.toList(),
    );
  });
}
```







