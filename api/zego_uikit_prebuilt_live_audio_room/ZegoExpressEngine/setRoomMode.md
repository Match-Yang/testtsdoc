


# setRoomMode method








Future&lt;void> setRoomMode
([ZegoRoomMode](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomMode.md) mode)





<p>Set room mode.</p>
<p>Available since: 2.9.0
Description: If you need to use the multi-room feature, please call this function to complete the configuration.
When to call: Must be set before calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> to take effect, otherwise it will fail.
Restrictions: If you need to use the multi-room feature, please contact the instant technical support to configure the server support.
Caution: None.</p>
<ul>
<li><code>mode</code> Room mode. Description: Used to set the room mode. Use cases: If you need to enter multiple rooms at the same time for publish-play stream, please turn on the multi-room mode through this interface. Required: True. Default value: ZEGO_ROOM_MODE_SINGLE_ROOM.</li>
</ul>



## Implementation

```dart
static Future<void> setRoomMode(ZegoRoomMode mode) async {
  return await ZegoExpressImpl.setRoomMode(mode);
}
```







