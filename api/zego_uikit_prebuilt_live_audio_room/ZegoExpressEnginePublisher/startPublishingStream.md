


# startPublishingStream method








Future&lt;void> startPublishingStream
(String streamID, {[ZegoPublisherConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig-class.md)? config, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Starts publishing a stream. Support multi-room mode.</p>
<p>Available since: 1.1.0
Description: Users push their local audio and video streams to the ZEGO RTC server or CDN, and other users in the same room can pull the audio and video streams to watch through the <code>streamID</code> or CDN pull stream address.
Use cases: It can be used to publish streams in real-time connecting wheat, live broadcast and other scenarios.
When to call: After <code>loginRoom</code>.
Restrictions: None.
Caution:</p>
<ol>
<li>Before start to publish the stream, the user can choose to call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setVideoConfig.md">setVideoConfig</a> to set the relevant video parameters, and call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md">startPreview</a> to preview the video.</li>
<li>Other users in the same room can get the streamID by monitoring the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStreamUpdate.md">onRoomStreamUpdate</a> event callback after the local user publishing stream successfully.</li>
<li>In the case of poor network quality, user publish may be interrupted, and the SDK will attempt to reconnect. You can learn about the current state and error information of the stream published by monitoring the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherStateUpdate.md">onPublisherStateUpdate</a> event.</li>
<li>To call <code>SetRoomMode</code> function to select multiple rooms, the room ID must be specified explicitly.</li>
</ol>
<ul>
<li><code>streamID</code> Stream ID, a string of up to 256 characters.
Caution:
<ol>
<li>Stream ID is defined by you.</li>
<li>needs to be globally unique within the entire AppID. If in the same AppID, different users publish each stream and the stream ID is the same, which will cause the user to publish the stream failure. You cannot include URL keywords, otherwise publishing stream and playing stream will fails.</li>
<li>Only support numbers, English characters and '-', '&nbsp;'.</li>
</ol>
</li>
<li><code>config</code> Advanced publish configuration.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> startPublishingStream(String streamID,
    {ZegoPublisherConfig? config, ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .startPublishingStream(streamID, config: config, channel: channel);
}
```







