


# logoutRoom method








Future&lt;[ZegoRoomLogoutResult](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomLogoutResult-class.md)> logoutRoom
([String? roomID])





<p>Logs out of a room.</p>
<p>Available since: 1.1.0
Description: This API will log out the room named roomID.
Use cases: In the same room, users can conduct live broadcast, audio and video calls, etc.
When to call /Trigger: After successfully logging in to the room, if the room is no longer used, the user can call the function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/logoutRoom.md">logoutRoom</a>.
Restrictions: None.
Caution: 1. Exiting the room will stop all publishing and playing streams for user, and inner audio and video engine will stop, and then SDK will auto stop local preview UI. If you want to keep the preview ability when switching rooms, please use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/switchRoom.md">switchRoom</a> method. 2. If the user logs in to the room, but the incoming 'roomID' is different from the logged-in room name, SDK will return failure.
Related callbacks: After calling this function, you will receive <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateChanged.md">onRoomStateChanged</a> (Not supported before 2.18.0, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateUpdate.md">onRoomStateUpdate</a>) callback notification successfully exits the room, while other users in the same room will receive the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomUserUpdate.md">onRoomUserUpdate</a> callback notification(On the premise of enabling isUserStatusNotify configuration).
Related APIs: Users can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/loginRoom.md">loginRoom</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/switchRoom.md">switchRoom</a> functions to log in or switch rooms.</p>
<ul>
<li><code>roomID</code> Room ID, a string of up to 128 bytes in length.
Caution:
<ol>
<li>Only support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.</li>
<li>If you need to communicate with the Web SDK, please do not use '%'.</li>
</ol>
</li>
<li>Returns The result of this logout room</li>
</ul>



## Implementation

```dart
Future<ZegoRoomLogoutResult> logoutRoom([String? roomID]) async {
  return await ZegoExpressImpl.instance.logoutRoom(roomID);
}
```







