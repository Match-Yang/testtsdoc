


# mutePlayStreamVideo method








Future&lt;void> mutePlayStreamVideo
(String streamID, bool mute)





<p>Whether the pull stream can receive the specified video data.</p>
<p>Available since: 1.1.0
Description: In the process of real-time video and video interaction, local users can use this function to control whether to receive video data from designated remote users when pulling streams as needed. When the developer does not receive the audio receipt, the hardware and network overhead can be reduced.
Use cases: This function can be called when developers need to quickly close and resume watching remote video. Compared to re-flow, it can greatly reduce the time and improve the interactive experience.
When to call: This function can be called after calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution: This function is valid only when the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo</a> function is set to <code>false</code>. When you mute the video stream, the view remains at the last frame by default, if you need to clear the last frame, please contact ZEGO technical support.
Related APIs: You can call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo</a> function to control whether to receive all video data. When the two functions <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo</a> are set to <code>false</code> at the same time, the local user can receive the video data of the remote user when the stream is pulled: 1. When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo(true)</a> function is called, it will take effect globally, that is, local users will be prohibited from receiving all remote users' video data. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo</a> function will not take effect whether it is called before or after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo</a>. 2. When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md">muteAllPlayStreamVideo(false)</a> function is called, the local user can receive the video data of all remote users. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo</a> function can be used to control whether to receive a single video data. Call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo(true, streamID)</a> function, the local user can receive other video data other than the <code>streamID</code>; call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md">mutePlayStreamVideo(false, streamID)</a> function, the local user can receive all the video data.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>mute</code> Whether it is possible to receive the video data of the specified remote user when streaming, "true" means prohibition, "false" means receiving, the default value is "false".</li>
</ul>



## Implementation

```dart
Future<void> mutePlayStreamVideo(String streamID, bool mute) async {
  return await ZegoExpressImpl.instance.mutePlayStreamVideo(streamID, mute);
}
```







