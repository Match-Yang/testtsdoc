


# setRoomAttributes method








Future&lt;[ZIMRoomAttributesOperatedCallResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesOperatedCallResult-class.md)> setRoomAttributes
(Map&lt;String, String> roomAttributes, String roomID, [ZIMRoomAttributesSetConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesSetConfig-class.md) config)





<p>Set room attributes (use this for all additions and changes).</p>
<p>Available since: 2.1.5.</p>
<p>Description: Used to set room properties.</p>
<p><code>roomAttributes</code> room attributes will be set.
<code>roomID</code> ID of the room to set.
<code>config</code> config of the room to set.</p>



## Implementation

```dart
Future<ZIMRoomAttributesOperatedCallResult> setRoomAttributes(
    Map<String, String> roomAttributes,
    String roomID,
    ZIMRoomAttributesSetConfig config);
```







