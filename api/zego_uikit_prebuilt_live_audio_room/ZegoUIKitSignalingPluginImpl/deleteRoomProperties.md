


# deleteRoomProperties method








Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)> deleteRoomProperties
({required String roomID, required List&lt;String> keys, bool isForce = false})

_<span class="feature">inherited</span>_



<p>delete room properties</p>



## Implementation

```dart
Future<ZegoSignalingPluginRoomPropertiesOperationResult>
    deleteRoomProperties({
  required String roomID,
  required List<String> keys,
  bool isForce = false,
}) async {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .deleteRoomProperties(roomID: roomID, keys: keys, isForce: isForce);
}
```







