


# deleteRoomAttributes method








Future&lt;[ZIMRoomAttributesOperatedCallResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesOperatedCallResult-class.md)> deleteRoomAttributes
(List&lt;String> keys, String roomID, [ZIMRoomAttributesDeleteConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesDeleteConfig-class.md) config)





<p>Delete room attributes.</p>
<p>Available since: 2.1.5.</p>
<p>Description: Used to delete room attributes.</p>
<p><code>keys</code> room attributes keys will be deleted.
<code>roomID</code> ID of the room to deleted.
<code>config</code> config of the room to deleted.</p>



## Implementation

```dart
Future<ZIMRoomAttributesOperatedCallResult> deleteRoomAttributes(
    List<String> keys, String roomID, ZIMRoomAttributesDeleteConfig config);
```







