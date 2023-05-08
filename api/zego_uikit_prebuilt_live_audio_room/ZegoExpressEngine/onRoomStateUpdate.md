


# onRoomStateUpdate property







(void Function(String roomID, [ZegoRoomState](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md) state, int errorCode, Map&lt;String, dynamic> extendedData)?) onRoomStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the room connection state changes.</p>
<p>Available since: 1.1.0
Description: This callback is triggered when the connection status of the room changes, and the reason for the change is notified.For versions 2.18.0 and above, it is recommended to use the onRoomStateChanged callback instead of the onRoomStateUpdate callback to monitor room state changes.
Use cases: Developers can use this callback to determine the status of the current user in the room.
When to trigger:</p>
<ol>
<li>The developer will receive this notification when calling the <code>loginRoom</code>, <code>logoutRoom</code>, <code>switchRoom</code> functions.</li>
<li>This notification may also be received when the network condition of the user's device changes (SDK will automatically log in to the room when disconnected, please refer to <code>Does ZEGO SDK support a fast reconnection for temporary disconnection</code> for details](<a href="https://docs.zegocloud.com/faq/reconnect?product=ExpressVideo&amp;platform=all">https://docs.zegocloud.com/faq/reconnect?product=ExpressVideo&amp;platform=all</a>).
Restrictions: None.
Caution: If the connection is being requested for a long time, the general probability is that the user's network is unstable.
Related APIs: <code>loginRoom</code>、<code>logoutRoom</code>、<code>switchRoom</code></li>
</ol>
<ul>
<li><code>roomID</code> Room ID, a string of up to 128 bytes in length.</li>
<li><code>state</code> Changed room state.</li>
<li><code>errorCode</code> Error code, For details, please refer to <a href="https://docs.zegocloud.com/article/5548">Common Error Codes</a>.</li>
<li><code>extendedData</code> Extended Information with state updates. When the room login is successful, the key "room_session_id" can be used to obtain the unique RoomSessionID of each audio and video communication, which identifies the continuous communication from the first user in the room to the end of the audio and video communication. It can be used in scenarios such as call quality scoring and call problem diagnosis.</li>
</ul>



## Implementation

```dart
static void Function(String roomID, ZegoRoomState state, int errorCode,
    Map<String, dynamic> extendedData)? onRoomStateUpdate;
```







