


# onRoomExtraInfoUpdate property







(void Function(String roomID, List&lt;[ZegoRoomExtraInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomExtraInfo-class.md)> roomExtraInfoList)?) onRoomExtraInfoUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when there is an update on the extra information of the room.</p>
<p>Available since: 1.1.0
Description: After the room extra information is updated, all users in the room will be notified except update the room extra information user.
Use cases: Extra information for the room.
When to call /Trigger: When a user update the room extra information, other users in the same room will receive the callback.
Restrictions: None.
Related APIs: Users can update room extra information through <code>setRoomExtraInfo</code> function.</p>
<ul>
<li><code>roomID</code> Room ID where the user is logged in, a string of up to 128 bytes in length.</li>
<li><code>roomExtraInfoList</code> List of the extra info updated.</li>
</ul>



## Implementation

```dart
static void Function(
        String roomID, List<ZegoRoomExtraInfo> roomExtraInfoList)?
    onRoomExtraInfoUpdate;
```







