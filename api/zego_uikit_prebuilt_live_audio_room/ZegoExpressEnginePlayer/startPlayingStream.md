


# startPlayingStream method








Future&lt;void> startPlayingStream
(String streamID, {[ZegoCanvas](../../zego_uikit_prebuilt_live_audio_room/ZegoCanvas-class.md)? canvas, [ZegoPlayerConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig-class.md)? config})





<p>Starts playing a stream from ZEGO RTC server or from third-party CDN. Support multi-room mode.</p>
<p>Available since: 1.1.0
Description: Play audio and video streams from the ZEGO RTC server or CDN.
Use cases: In real-time or live broadcast scenarios, developers can listen to the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStreamUpdate.md">onRoomStreamUpdate</a> event callback to obtain the new stream information in the room where they are located, and call this interface to pass in streamID for play streams.
When to call: After <code>loginRoom</code>.
Restrictions: None.
Caution: 1. The developer can update the player canvas by calling this function again (the streamID must be the same). 2. After the first play stream failure due to network reasons or the play stream is interrupted, the default time for SDK reconnection is 20min. 3. In the case of poor network quality, user play may be interrupted, the SDK will try to reconnect, and the current play status and error information can be obtained by listening to the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerStateUpdate.md">onPlayerStateUpdate</a> event. please refer to <a href="https://docs.zegocloud.com/faq/reconnect">https://docs.zegocloud.com/faq/reconnect</a>. 4. Playing the stream ID that does not exist, the SDK continues to try to play after calling this function. After the stream ID is successfully published, the audio and video stream can be actually played.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>streamID</code> Stream ID, a string of up to 256 characters.
Caution:
<ol>
<li>Only support numbers, English characters and '-', '&nbsp;'.</li>
</ol>
</li>
<li><code>canvas</code> The view used to display the play audio and video stream's image. When the view is set to <code>null</code>, no video is displayed, only audio is played.</li>
<li><code>config</code> Advanced player configuration.</li>
</ul>



## Implementation

```dart
Future<void> startPlayingStream(String streamID,
    {ZegoCanvas? canvas, ZegoPlayerConfig? config}) async {
  return await ZegoExpressImpl.instance
      .startPlayingStream(streamID, canvas: canvas, config: config);
}
```







