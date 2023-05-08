


# muteAllPlayStreamAudio method








Future&lt;void> muteAllPlayStreamAudio
(bool mute)





<p>Can the pull stream receive all audio data.</p>
<p>Available since: 2.4.0
Description: In the process of real-time audio and video interaction, local users can use this function to control whether to receive audio data from all remote users when pulling streams (including the audio streams pushed by users who have newly joined the room after calling this function). By default, users can receive audio data pushed by all remote users after joining the room. When the developer does not receive the audio receipt, the hardware and network overhead can be reduced.
Use cases: Call this function when developers need to quickly close and restore remote audio. Compared to re-flow, it can greatly reduce the time and improve the interactive experience.
When to call: This function can be called after calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Related APIs: You can call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a> function to control whether to receive a single piece of audio data. When the two functions <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a> are set to <code>false</code> at the same time, the local user can receive the audio data of the remote user when the stream is pulled: 1. When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio(true)</a> function is called, it takes effect globally, that is, local users will be prohibited from receiving audio data from all remote users. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a> function will not take effect no matter if the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a> function is called before or after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio</a>. 2. When the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md">muteAllPlayStreamAudio(false)</a> function is called, the local user can receive the audio data of all remote users. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio</a> function can be used to control whether to receive a single audio data. Calling the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio(true, streamID)</a> function allows the local user to receive audio data other than the <code>streamID</code>; calling the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md">mutePlayStreamAudio(false, streamID)</a> function allows the local user to receive all audio data.</p>
<ul>
<li><code>mute</code> Whether it is possible to receive audio data from all remote users when streaming, "true" means prohibition, "false" means receiving, and the default value is "false".</li>
</ul>



## Implementation

```dart
Future<void> muteAllPlayStreamAudio(bool mute) async {
  return await ZegoExpressImpl.instance.muteAllPlayStreamAudio(mute);
}
```







