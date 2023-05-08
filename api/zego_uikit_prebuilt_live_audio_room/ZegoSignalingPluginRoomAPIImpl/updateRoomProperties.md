


# updateRoomProperties method







- @override

Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)> updateRoomProperties
({required String roomID, required Map&lt;String, String> roomProperties, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false})

_<span class="feature">override</span>_



<p>update room properties</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginRoomPropertiesOperationResult>
    updateRoomProperties({
  required String roomID,
  required Map<String, String> roomProperties,
  bool isForce = false,
  bool isDeleteAfterOwnerLeft = false,
  bool isUpdateOwner = false,
}) async {
  return ZIM
      .getInstance()!
      .setRoomAttributes(
        roomProperties,
        roomID,
        ZIMRoomAttributesSetConfig()
          ..isForce = isForce
          ..isDeleteAfterOwnerLeft = isDeleteAfterOwnerLeft
          ..isUpdateOwner = isUpdateOwner,
      )
      .then((zimResult) {
    return ZegoSignalingPluginRoomPropertiesOperationResult(
      errorKeys: zimResult.errorKeys,
    );
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'update room properties, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginRoomPropertiesOperationResult(
      error: error,
      errorKeys: roomProperties.keys.toList(),
    );
  });
}
```







