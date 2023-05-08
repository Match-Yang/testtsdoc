


# onRoomStreamExtraInfoUpdate property







(void Function(String roomID, List&lt;[ZegoStream](../../zego_uikit_prebuilt_live_audio_room/ZegoStream-class.md)> streamList)?) onRoomStreamExtraInfoUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when there is an update on the extra information of the streams published by other users in the same room.</p>
<p>Available since: 1.1.0
Description: All users in the room will be notified by this callback when the extra information of the stream in the room is updated.
Use cases: Users can realize some business functions through the characteristics of stream extra information consistent with stream life cycle.
When to call /Trigger: When a user publishing the stream update the extra information of the stream in the same room, other users in the same room will receive the callback.
Restrictions: None.
Caution: Unlike the stream ID, which cannot be modified during the publishing process, the stream extra information can be updated during the life cycle of the corresponding stream ID.
Related APIs: Users who publish stream can set extra stream information through <code>setStreamExtraInfo</code>.</p>
<ul>
<li><code>roomID</code> Room ID where the user is logged in, a string of up to 128 bytes in length.</li>
<li><code>streamList</code> List of streams that the extra info was updated.</li>
</ul>



## Implementation

```dart
static void Function(String roomID, List<ZegoStream> streamList)?
    onRoomStreamExtraInfoUpdate;
```







