


# stopPublishingStream method








Future&lt;void> stopPublishingStream
({[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Stops publishing a stream (for the specified channel).</p>
<p>Available since: 1.1.0
Description: The user stops sending local audio and video streams, and other users in the room will receive a stream deletion notification.
Use cases: It can be used to stop publish streams in real-time connecting wheat, live broadcast and other scenarios.
When to call: After <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>.
Restrictions: None.
Caution:</p>
<ol>
<li>After stopping the streaming, other users in the same room can receive the delete notification of the stream by listening to the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStreamUpdate.md">onRoomStreamUpdate</a> callback.</li>
<li>If the user has initiated publish flow, this function must be called to stop the publish of the current stream before publishing the new stream (new streamID), otherwise the new stream publish will return a failure.</li>
<li>After stopping streaming, the developer should stop the local preview based on whether the business situation requires it.</li>
</ol>
<ul>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> stopPublishingStream({ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .stopPublishingStream(channel: channel);
}
```







