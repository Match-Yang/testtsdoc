


# stopPlayingStream method








Future&lt;void> stopPlayingStream
(String streamID)





<p>Stops playing a stream.</p>
<p>Available since: 1.1.0
Description: Play audio and video streams from the ZEGO RTC server.
Use cases: In the real-time scenario, developers can listen to the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStreamUpdate.md">onRoomStreamUpdate</a> event callback to obtain the delete stream information in the room where they are located, and call this interface to pass in streamID for stop play streams.
When to call: After <code>loginRoom</code>.
Restrictions: None.
Caution: When stopped, the attributes set for this stream previously, such as <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayVolume.md">setPlayVolume</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo</a>, etc., will be invalid and need to be reset when playing the the stream next time.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
</ul>



## Implementation

```dart
Future<void> stopPlayingStream(String streamID) async {
  return await ZegoExpressImpl.instance.stopPlayingStream(streamID);
}
```







