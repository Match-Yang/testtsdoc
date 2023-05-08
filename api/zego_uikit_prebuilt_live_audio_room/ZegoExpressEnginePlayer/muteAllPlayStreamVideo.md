


# muteAllPlayStreamVideo method








Future&lt;void> muteAllPlayStreamVideo
(bool mute)





<p>Can the pull stream receive all video data.</p>
<p>Available since: 2.4.0
Description: In the process of real-time video and video interaction, local users can use this function to control whether to receive all remote users' video data when pulling the stream (including the video stream pushed by the new user who joins the room after calling this function). By default, users can receive video data pushed by all remote users after joining the room. When the developer does not receive the audio receipt, the hardware and network overhead can be reduced.
Use cases: This function can be called when developers need to quickly close and resume watching remote video. Compared to re-flow, it can greatly reduce the time and improve the interactive experience.
When to call: This function can be called after calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution: When you mute the video stream, the view remains at the last frame by default, if you need to clear the last frame, please contact ZEGO technical support.
Related APIs: You can call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo</a> function to control whether to receive a single piece of video data. When the two functions <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo</a> are set to <code>false</code> at the same time, the local user can receive the video data of the remote user when the stream is pulled: 1. When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo(true)</a> function is called, it will take effect globally, that is, the local user will be prohibited from receiving all remote users' video data. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo</a> function will not take effect whether it is called before or after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo</a>. 2. When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo(false)</a> function is called, the local user can receive the video data of all remote users. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo</a> function can be used to control whether to receive a single video data. Call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo(true, streamID)</a> function, the local user can receive other video data other than the <code>streamID</code>; call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo(false, streamID)</a> function, the local user can receive all the video data.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>mute</code> Whether it is possible to receive all remote users' video data when streaming, "true" means prohibition, "false" means receiving, and the default value is "false".</li>
</ul>



## Implementation

```dart
Future<void> muteAllPlayStreamVideo(bool mute) async {
  return await ZegoExpressImpl.instance.muteAllPlayStreamVideo(mute);
}
```







