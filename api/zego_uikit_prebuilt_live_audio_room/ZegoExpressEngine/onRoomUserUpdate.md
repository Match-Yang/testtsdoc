


# onRoomUserUpdate property







(void Function(String roomID, [ZegoUpdateType](../../zego_uikit_prebuilt_live_audio_room/ZegoUpdateType.md) updateType, List&lt;[ZegoUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUser-class.md)> userList)?) onRoomUserUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the number of other users in the room increases or decreases.</p>
<p>Available since: 1.1.0
Description: When other users in the room are online or offline, which causes the user list in the room to change, the developer will be notified through this callback.
Use cases: Developers can use this callback to update the user list display in the room in real time.
When to trigger:</p>
<ol>
<li>When the user logs in to the room for the first time, if there are other users in the room, the SDK will trigger a callback notification with <code>updateType</code> being <code>ZegoUpdateTypeAdd</code>, and <code>userList</code> is the other users in the room at this time.</li>
<li>The user is already in the room. If another user logs in to the room through the <code>loginRoom</code> or <code>switchRoom</code> functions, the SDK will trigger a callback notification with <code>updateType</code> being <code>ZegoUpdateTypeAdd</code>.</li>
<li>If other users log out of this room through the <code>logoutRoom</code> or <code>switchRoom</code> functions, the SDK will trigger a callback notification with <code>updateType</code> being <code>ZegoUpdateTypeDelete</code>.</li>
<li>The user is already in the room. If another user is kicked out of the room from the server, the SDK will trigger a callback notification with <code>updateType</code> being <code>ZegoUpdateTypeDelete</code>.
Restrictions: If developers need to use ZEGO room users notifications, please ensure that the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig-class.md">ZegoRoomConfig</a> sent by each user when logging in to the room has the <code>isUserStatusNotify</code> property set to true, otherwise the callback notification will not be received.
Related APIs: <code>loginRoom</code>、<code>logoutRoom</code>、<code>switchRoom</code></li>
</ol>
<ul>
<li><code>roomID</code> Room ID where the user is logged in, a string of up to 128 bytes in length.</li>
<li><code>updateType</code> Update type (add/delete).</li>
<li><code>userList</code> List of users changed in the current room.</li>
</ul>



## Implementation

```dart
static void Function(
        String roomID, ZegoUpdateType updateType, List<ZegoUser> userList)?
    onRoomUserUpdate;
```







