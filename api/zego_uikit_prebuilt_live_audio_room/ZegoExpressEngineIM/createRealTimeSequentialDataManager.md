


# createRealTimeSequentialDataManager method








Future&lt;[ZegoRealTimeSequentialDataManager](../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md)?> createRealTimeSequentialDataManager
(String roomID)





<p>Create the real time sequential data manager instance</p>
<p>Available: since 2.14.0
Description: Create a manager object for sending/receiving real-time signaling.
Use cases: You can use this function when you need to use real-time signaling to implement services such as cloud games and remote desktops.
When to call: After logging in to a room.
Restrictions: Only one corresponding manager object can be created for each room ID of <code>loginRoom</code>, that is, only one object can be created in single room mode, and multiple objects can be created in multi-room mode.
Caution: If you create this object before using the audio and video function (push/pull streaming), the camera and microphone will be automatically closed. If the user has not called <code>enableCamera</code> / <code>enableAudioCaptureDevice</code> before the object is destroyed, it will be destroyed After this object, the SDK will automatically restore the camera and microphone.</p>
<ul>
<li><code>roomID</code> Fill in the room ID that has been logged in, and all related stuff will be do in this room.</li>
<li>Returns The real-time sequential data manager instance, null will be returned when the maximum number is exceeded.</li>
</ul>



## Implementation

```dart
Future<ZegoRealTimeSequentialDataManager?>
    createRealTimeSequentialDataManager(String roomID) async {
  return await ZegoExpressImpl.instance
      .createRealTimeSequentialDataManager(roomID);
}
```







