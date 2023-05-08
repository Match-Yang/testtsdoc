


# queryRoomProperties method








Future&lt;[ZegoSignalingPluginQueryRoomPropertiesResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryRoomPropertiesResult-class.md)> queryRoomProperties
({required String roomID})

_<span class="feature">inherited</span>_



<p>query room properties</p>



## Implementation

```dart
Future<ZegoSignalingPluginQueryRoomPropertiesResult> queryRoomProperties({
  required String roomID,
}) async {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .queryRoomProperties(roomID: roomID);
}
```







