


# setRoomExtraInfo method








Future&lt;[ZegoRoomSetRoomExtraInfoResult](../../zego_uikit_prebuilt_live_audio_room/ZegoRoomSetRoomExtraInfoResult-class.md)> setRoomExtraInfo
(String roomID, String key, String value)





<p>Set room extra information.</p>
<p>Available since: 1.13.0
Description: The user can call this function to set the extra info of the room.
Use cases: You can set some room-related business attributes, such as whether someone is Co-hosting.
When to call /Trigger: After logging in the room successful.
Restrictions: For restrictions on the use of this function, please refer to <a href="https://docs.zegocloud.com/article/7611">https://docs.zegocloud.com/article/7611</a> or contact ZEGO technical support.
Caution: 'key' is non null. The length of key and value is limited, please refer to Restrictions. The newly set key and value will overwrite the old setting.
Related callbacks: Other users in the same room will be notified through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomExtraInfoUpdate.md">onRoomExtraInfoUpdate</a> callback function.
Related APIs: None.</p>
<ul>
<li><code>roomID</code> Room ID.</li>
<li><code>key</code> key of the extra info.</li>
<li><code>value</code> value if the extra info.</li>
<li>Returns Set room extra info execution result notification</li>
</ul>



## Implementation

```dart
Future<ZegoRoomSetRoomExtraInfoResult> setRoomExtraInfo(
    String roomID, String key, String value) async {
  return await ZegoExpressImpl.instance.setRoomExtraInfo(roomID, key, value);
}
```







