


# switchRoom method








Future&lt;void> switchRoom
(String fromRoomID, String toRoomID, {[ZegoRoomConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig-class.md)? config})





<p>Switch the room with advanced room configurations.</p>
<p>Available since: 1.15.0
Description: Using this interface allows users to quickly switch from one room to another room.
Use cases: if you need to quickly switch to the next room, you can call this function.
When to call /Trigger: After successfully login room.
Restrictions: None.
Caution:</p>
<ol>
<li>When this function is called, all streams currently publishing or playing will stop (but the local preview will not stop).</li>
<li>To prevent the app from being impersonated by a malicious user, you can add authentication before logging in to the room, that is, the <code>token</code> parameter in the ZegoRoomConfig object passed in by the <code>config</code> parameter. This parameter configuration affects the room to be switched over. 3. When the function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setRoomMode.md">setRoomMode</a> is used to set ZegoRoomMode to ZEGO_ROOM_MODE_MULTI_ROOM, this function is not available.
Privacy reminder: Please do not fill in sensitive user information in this interface, including but not limited to mobile phone number, ID number, passport number, real name, etc.
Related callbacks: When the user call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/switchRoom.md">switchRoom</a> function, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateChanged.md">onRoomStateChanged</a> (Not supported before 2.18.0, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateUpdate.md">onRoomStateUpdate</a>) callback will be triggered to notify the developer of the status of the current user connected to the room.
Related APIs: Users can use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/logoutRoom.md">logoutRoom</a> function to log out of the room.</li>
</ol>
<ul>
<li><code>fromRoomID</code> Current roomID.</li>
<li><code>toRoomID</code> The next roomID.</li>
<li><code>config</code> Advanced room configuration.</li>
</ul>



## Implementation

```dart
Future<void> switchRoom(String fromRoomID, String toRoomID,
    {ZegoRoomConfig? config}) async {
  return await ZegoExpressImpl.instance
      .switchRoom(fromRoomID, toRoomID, config: config);
}
```







