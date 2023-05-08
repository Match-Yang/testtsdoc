


# endRoomAttributesBatchOperation method








Future&lt;[ZIMRoomAttributesBatchOperatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesBatchOperatedResult-class.md)> endRoomAttributesBatchOperation
(String roomID)





<p>Complete the property operation of the combined room.</p>
<p>Available since: 2.1.5.</p>
<p>Description: After completing the operation of combining room attributes,
all the setting/deleting operations from the last call to beginRoomAttributesBatchOperation
to this operation will be completed for the room.</p>
<p><code>roomID</code> ID of the room to operation.</p>



## Implementation

```dart
Future<ZIMRoomAttributesBatchOperatedResult> endRoomAttributesBatchOperation(
    String roomID);
```







