


# onPlayerRecvAudioFirstFrame property







(void Function(String streamID)?) onPlayerRecvAudioFirstFrame
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the first audio frame is received.</p>
<p>Available since: 1.1.0
Description: After the <code>startPlayingStream</code> function is called successfully, this callback will be called when SDK received the first frame of audio data.
Use cases: Developer can use this callback to count time consuming that take the first frame time or update the UI for playing stream.
Trigger: This callback is triggered when SDK receives the first frame of audio data from the network.
Related callbacks: After a successful call to <code>startPlayingStream</code>, the callback function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRecvVideoFirstFrame.md">onPlayerRecvVideoFirstFrame</a> determines whether the SDK has received the video data, and the callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRenderVideoFirstFrame.md">onPlayerRenderVideoFirstFrame</a> determines whether the SDK has rendered the first frame of the received video data.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
</ul>



## Implementation

```dart
static void Function(String streamID)? onPlayerRecvAudioFirstFrame;
```







