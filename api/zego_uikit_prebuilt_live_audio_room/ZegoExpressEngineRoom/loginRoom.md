


# loginRoom method








Future&lt;[ZegoRoomLoginResult](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomLoginResult-class.md)> loginRoom
(String roomID, [ZegoUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUser-class.md) user, {[ZegoRoomConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig-class.md)? config})





<p>Log in to the room by configuring advanced properties, and return the login result through the callback parameter. You must log in to the room before pushing or pulling the stream.</p>
<p>Available since: 2.18.0
Description: If the room does not exist, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/loginRoom.md">loginRoom</a> creates and logs in the room. SDK uses the 'room' to organize users. After users log in to a room, they can use interface such as push stream <code>startPublishingStream</code>, pull stream <code>startPlayingStream</code>, send and receive broadcast messages <code>sendBroadcastMessage</code>, etc. To prevent the app from being impersonated by a malicious user, you can add authentication before logging in to the room, that is, the <code>token</code> parameter in the ZegoRoomConfig object passed in by the <code>config</code> parameter.
Use cases: In the same room, users can conduct live broadcast, audio and video calls, etc.
When to call /Trigger: This interface is called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> initializes the SDK.
Restrictions: For restrictions on the use of this function, please refer to <a href="https://docs.zegocloud.com/article/7611">https://docs.zegocloud.com/article/7611</a> or contact ZEGO technical support.
Caution:</p>
<ol>
<li>Apps that use different appIDs cannot intercommunication with each other.</li>
<li>SDK supports startPlayingStream audio and video streams from different rooms under the same appID, that is, startPlayingStream audio and video streams across rooms. Since ZegoExpressEngine's room related callback notifications are based on the same room, when developers want to startPlayingStream streams across rooms, developers need to maintain related messages and signaling notifications by themselves.</li>
<li>It is strongly recommended that userID corresponds to the user ID of the business APP, that is, a userID and a real user are fixed and unique, and should not be passed to the SDK in a random userID. Because the unique and fixed userID allows ZEGO technicians to quickly locate online problems.</li>
<li>After the first login failure due to network reasons or the room is disconnected, the default time of SDK reconnection is 20min.</li>
<li>After the user has successfully logged in to the room, if the application exits abnormally, after restarting the application, the developer needs to call the logoutRoom interface to log out of the room, and then call the loginRoom interface to log in to the room again.
Privacy reminder: Please do not fill in sensitive user information in this interface, including but not limited to mobile phone number, ID number, passport number, real name, etc.
Related callbacks:</li>
<li>When the user starts to log in to the room, the room is successfully logged in, or the room fails to log in, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateChanged.md">onRoomStateChanged</a> (Not supported before 2.18.0, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateUpdate.md">onRoomStateUpdate</a>) callback will be triggered to notify the developer of the status of the current user connected to the room.</li>
<li>Different users who log in to the same room can get room related notifications in the same room (eg <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomUserUpdate.md">onRoomUserUpdate</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStreamUpdate.md">onRoomStreamUpdate</a>, etc.), and users in one room cannot receive room signaling notifications in another room.</li>
<li>If the network is temporarily interrupted due to network quality reasons, the SDK will automatically reconnect internally. You can get the current connection status of the local room by listening to the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateChanged.md">onRoomStateChanged</a> (Not supported before 2.18.0, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateUpdate.md">onRoomStateUpdate</a>) callback method, and other users in the same room will receive <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomUserUpdate.md">onRoomUserUpdate</a> callback notification.</li>
<li>Messages sent in one room (e.g. <code>setStreamExtraInfo</code>, <code>sendBroadcastMessage</code>, <code>sendBarrageMessage</code>, <code>sendCustomCommand</code>, etc.) cannot be received callback ((eg <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStreamExtraInfoUpdate.md">onRoomStreamExtraInfoUpdate</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBroadcastMessage.md">onIMRecvBroadcastMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBarrageMessage.md">onIMRecvBarrageMessage</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvCustomCommand.md">onIMRecvCustomCommand</a>, etc) in other rooms. Currently, SDK does not provide the ability to send messages across rooms. Developers can integrate the SDK of third-party IM to achieve.
Related APIs:</li>
<li>Users can call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/logoutRoom.md">logoutRoom</a> to log out. In the case that a user has successfully logged in and has not logged out, if the login interface is called again, the console will report an error and print the error code 1002001.</li>
<li>SDK supports multi-room login, please call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setRoomMode.md">setRoomMode</a> function to select multi-room mode before engine initialization, and then call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/loginRoom.md">loginRoom</a> to log in to multi-room.</li>
<li>Calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/destroyEngine.md">destroyEngine</a> will also automatically log out.</li>
</ol>
<ul>
<li><code>roomID</code> Room ID, a string of up to 128 bytes in length.
Caution:
<ol>
<li>room ID is defined by yourself.</li>
<li>Only support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.</li>
<li>If you need to communicate with the Web SDK, please do not use '%'.</li>
</ol>
</li>
<li><code>user</code> User object instance, configure userID, userName. Note that the userID needs to be globally unique with the same appID, otherwise the user who logs in later will kick out the user who logged in first.</li>
<li><code>config</code> Advanced room configuration.</li>
<li>Returns The result of this login room</li>
</ul>



## Implementation

```dart
Future<ZegoRoomLoginResult> loginRoom(String roomID, ZegoUser user,
    {ZegoRoomConfig? config}) async {
  return await ZegoExpressImpl.instance
      .loginRoom(roomID, user, config: config);
}
```







