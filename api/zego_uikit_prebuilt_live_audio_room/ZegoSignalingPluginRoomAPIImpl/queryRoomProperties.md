


# queryRoomProperties method







- @override

Future&lt;[ZegoSignalingPluginQueryRoomPropertiesResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryRoomPropertiesResult-class.md)> queryRoomProperties
({required String roomID})

_<span class="feature">override</span>_



<p>query room properties</p>



## Implementation

```dart
@override
Future<ZegoSignalingPluginQueryRoomPropertiesResult> queryRoomProperties({
  required String roomID,
}) {
  return ZIM
      .getInstance()!
      .queryRoomAllAttributes(roomID)
      .then((zimResult) => ZegoSignalingPluginQueryRoomPropertiesResult(
            properties: zimResult.roomAttributes,
          ))
      .catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'query room properties, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginQueryRoomPropertiesResult(
      error: error,
      properties: const {},
    );
  });
}
```







