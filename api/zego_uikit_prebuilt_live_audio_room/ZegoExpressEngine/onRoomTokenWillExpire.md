


# onRoomTokenWillExpire property







(void Function(String roomID, int remainTimeInSecond)?) onRoomTokenWillExpire
  
_<span class="feature">read / write</span>_



<p>Callback notification that room Token authentication is about to expire.</p>
<p>Available since: 2.8.0
Description: The callback notification that the room Token authentication is about to expire, please use <code>renewToken</code> to update the room Token authentication.
Use cases: In order to prevent illegal entry into the room, it is necessary to perform authentication control on login room, push streaming, etc., to improve security.
When to call /Trigger: 30 seconds before the Token expires, the SDK will call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomTokenWillExpire.md">onRoomTokenWillExpire</a> to notify developer.
Restrictions: None.
Caution: The token contains important information such as the user's room permissions, publish stream permissions, and effective time, please refer to <a href="https://docs.zegocloud.com/article/11649">https://docs.zegocloud.com/article/11649</a>.
Related APIs: When the developer receives this callback, he can use <code>renewToken</code> to update the token authentication information.</p>
<ul>
<li><code>roomID</code> Room ID where the user is logged in, a string of up to 128 bytes in length.</li>
<li><code>remainTimeInSecond</code> The remaining time before the token expires.</li>
</ul>



## Implementation

```dart
static void Function(String roomID, int remainTimeInSecond)?
    onRoomTokenWillExpire;
```







