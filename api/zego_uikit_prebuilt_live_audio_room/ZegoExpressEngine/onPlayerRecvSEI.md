


# onPlayerRecvSEI property







(void Function(String streamID, Uint8List data)?) onPlayerRecvSEI
  
_<span class="feature">read / write</span>_



<p>The callback triggered when Supplemental Enhancement Information is received.</p>
<p>Available since: 1.1.0
Description: After the <code>startPlayingStream</code> function is called successfully, when the remote stream sends SEI (such as directly calling <code>sendSEI</code>, audio mixing with SEI data, and sending custom video capture encoded data with SEI, etc.), the local end will receive this callback.
Trigger: After the <code>startPlayingStream</code> function is called successfully, when the remote stream sends SEI, the local end will receive this callback.
Caution: 1. Since the video encoder itself generates an SEI with a payload type of 5, or when a video file is used for publishing, such SEI may also exist in the video file. Therefore, if the developer needs to filter out this type of SEI, it can be before <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> Call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoEngineConfig/advancedConfig.md">ZegoEngineConfig.advancedConfig("unregister_sei_filter", "XXXXX")</a>. Among them, unregister_sei_filter is the key, and XXXXX is the uuid filter string to be set. 2. When <code>mutePlayStreamVideo</code> or <code>muteAllPlayStreamVideo</code> is called to set only the audio stream to be pulled, the SEI will not be received.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>data</code> SEI content.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, Uint8List data)? onPlayerRecvSEI;
```







