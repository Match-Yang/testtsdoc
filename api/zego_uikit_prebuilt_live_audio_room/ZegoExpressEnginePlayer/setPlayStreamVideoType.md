


# setPlayStreamVideoType method








Future&lt;void> setPlayStreamVideoType
(String streamID, [ZegoVideoStreamType](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoStreamType.md) streamType)





<p>Set play video stream type.</p>
<p>Available since: 2.3.0
Description: When the publish stream sets the codecID to SVC through <code>setVideoConfig</code>, the puller can dynamically set and select different stream types (small resolution is one-half of the standard layer).
Use cases: In general, when the network is weak or the rendered UI window is small, you can choose to pull videos with small resolutions to save bandwidth.
When to call: before or after called <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/startPlayingStream.md">startPlayingStream</a>.
Restrictions: None.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>streamType</code> Video stream type.</li>
</ul>



## Implementation

```dart
Future<void> setPlayStreamVideoType(
    String streamID, ZegoVideoStreamType streamType) async {
  return await ZegoExpressImpl.instance
      .setPlayStreamVideoType(streamID, streamType);
}
```







