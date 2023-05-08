


# onRoomStateChanged property







(void Function(String roomID, [ZegoRoomStateChangedReason](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) reason, int errorCode, Map&lt;String, dynamic> extendedData)?) onRoomStateChanged
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the room connection state changes.</p>
<p>Available since: 2.18.0
Description: This callback is triggered when the connection status of the room changes, and the reason for the change is notified.For versions 2.18.0 and above, it is recommended to use the onRoomStateChanged callback instead of the onRoomStateUpdate callback to monitor room state changes.
Use cases: Developers can use this callback to determine the status of the current user in the room.
When to trigger: Users will receive this notification when they call room functions (refer to <code>Related APIs</code>). 2. This notification may also be received when the user device's network conditions change (SDK will automatically log in to the room again when the connection is disconnected, refer to <a href="https://doc-zh.zego.im/faq/reconnect">https://doc-zh.zego.im/faq/reconnect</a> ).
Restrictions: None.
Caution: If the connection is being requested for a long time, the general probability is that the user's network is unstable.
Related APIs: <code>loginRoom</code>, <code>logoutRoom</code>, <code>switchRoom</code></p>
<ul>
<li><code>roomID</code> Room ID, a string of up to 128 bytes in length.</li>
<li><code>reason</code> Room state change reason.</li>
<li><code>errorCode</code> Error code, please refer to the error codes document <a href="https://doc-en.zego.im/en/5548.html">https://doc-en.zego.im/en/5548.html</a> for details.</li>
<li><code>extendedData</code> Extended Information with state updates. When the room login is successful, the key "room_session_id" can be used to obtain the unique RoomSessionID of each audio and video communication, which identifies the continuous communication from the first user in the room to the end of the audio and video communication. It can be used in scenarios such as call quality scoring and call problem diagnosis.</li>
</ul>



## Implementation

```dart
static void Function(String roomID, ZegoRoomStateChangedReason reason,
    int errorCode, Map<String, dynamic> extendedData)? onRoomStateChanged;
```







