


# onRoomStreamUpdate property







(void Function(String roomID, [ZegoUpdateType](../../zego_uikit_prebuilt_live_audio_room/ZegoUpdateType.md) updateType, List&lt;[ZegoStream](../../zego_uikit_prebuilt_live_audio_room/ZegoStream-class.md)> streamList, Map&lt;String, dynamic> extendedData)?) onRoomStreamUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the number of streams published by the other users in the same room increases or decreases.</p>
<p>Available since: 1.1.0
Description: When other users in the room start streaming or stop streaming, the streaming list in the room changes, and the developer will be notified through this callback.
Use cases: This callback is used to monitor stream addition or stream deletion notifications of other users in the room. Developers can use this callback to determine whether other users in the same room start or stop publishing stream, so as to achieve active playing stream <code>startPlayingStream</code> or take the initiative to stop the playing stream <code>stopPlayingStream</code>, and use it to change the UI controls at the same time.
When to trigger:</p>
<ol>
<li>When the user logs in to the room for the first time, if there are other users publishing streams in the room, the SDK will trigger a callback notification with <code>updateType</code> being <code>ZegoUpdateTypeAdd</code>, and <code>streamList</code> is an existing stream list.</li>
<li>The user is already in the room. if another user adds a new push, the SDK will trigger a callback notification with <code>updateType</code> being <code>ZegoUpdateTypeAdd</code>.</li>
<li>The user is already in the room. If other users stop streaming, the SDK will trigger a callback notification with <code>updateType</code> being <code>ZegoUpdateTypeDelete</code>.</li>
<li>The user is already in the room. If other users leave the room, the SDK will trigger a callback notification with <code>updateType</code> being <code>ZegoUpdateTypeDelete</code>.
Restrictions: None.</li>
</ol>
<ul>
<li><code>roomID</code> Room ID where the user is logged in, a string of up to 128 bytes in length.</li>
<li><code>updateType</code> Update type (add/delete).</li>
<li><code>streamList</code> Updated stream list.</li>
<li><code>extendedData</code> Extended information with stream updates.When receiving a stream deletion notification, the developer can convert the string into a json object to get the stream_delete_reason field, which is an array of stream deletion reasons, and the stream_delete_reason[].code field may have the following values: 1 (the user actively stops publishing stream) ; 2 (user heartbeat timeout); 3 (user repeated login); 4 (user kicked out); 5 (user disconnected); 6 (removed by the server).</li>
</ul>



## Implementation

```dart
static void Function(
    String roomID,
    ZegoUpdateType updateType,
    List<ZegoStream> streamList,
    Map<String, dynamic> extendedData)? onRoomStreamUpdate;
```







