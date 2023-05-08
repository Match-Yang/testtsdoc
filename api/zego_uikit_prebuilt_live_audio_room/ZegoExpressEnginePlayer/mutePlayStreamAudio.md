


# mutePlayStreamAudio method








Future&lt;void> mutePlayStreamAudio
(String streamID, bool mute)





<p>Whether the pull stream can receive the specified audio data.</p>
<p>Available since: 1.1.0
Description: In the process of real-time audio and video interaction, local users can use this function to control whether to receive audio data from designated remote users when pulling streams as needed. When the developer does not receive the audio receipt, the hardware and network overhead can be reduced.
Use cases: Call this function when developers need to quickly close and restore remote audio. Compared to re-flow, it can greatly reduce the time and improve the interactive experience.
When to call: This function can be called after calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution: This function is valid only when the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio</a> function is set to <code>false</code>.
Related APIs: You can call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio</a> function to control whether to receive all audio data. When the two functions <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a> are set to <code>false</code> at the same time, the local user can receive the audio data of the remote user when the stream is pulled: 1. When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio(true)</a> function is called, it is globally effective, that is, local users will be prohibited from receiving all remote users' audio data. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a> function will not take effect whether it is called before or after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio</a>.2. When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio(false)</a> function is called, the local user can receive the audio data of all remote users. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a> function can be used to control whether to receive a single audio data. Calling the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio(true, streamID)</a> function allows the local user to receive audio data other than the <code>streamID</code>; calling the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio(false, streamID)</a> function allows the local user to receive all audio data.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>mute</code> Whether it can receive the audio data of the specified remote user when streaming, "true" means prohibition, "false" means receiving, the default value is "false".</li>
</ul>



## Implementation

```dart
Future<void> mutePlayStreamAudio(String streamID, bool mute) async {
  return await ZegoExpressImpl.instance.mutePlayStreamAudio(streamID, mute);
}
```







