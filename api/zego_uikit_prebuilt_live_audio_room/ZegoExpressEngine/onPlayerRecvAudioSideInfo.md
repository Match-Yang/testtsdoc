


# onPlayerRecvAudioSideInfo property







(void Function(String streamID, Uint8List data)?) onPlayerRecvAudioSideInfo
  
_<span class="feature">read / write</span>_



<p>Receive the audio side information content of the remote stream.</p>
<p>Available since: 2.19.0
Description: After the <code>startPlayingStream</code> function is called successfully, when the remote stream sends audio side information, the local end will receive this callback.
Trigger: After the <code>startPlayingStream</code> function is called successfully, when the remote stream sends audio side information, the local end will receive this callback.
Caution: 1. When <code>mutePlayStreamAudio</code> or <code>muteAllPlayStreamAudio</code> is called to set only the video stream to be pulled, the audio side information not be received. 2. Due to factors such as the network, the received data may be missing, but the order is guaranteed.
Related APIs: Send audio side information by the <code>sendAudioSideInfo</code> function.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>data</code> Audio side information content.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, Uint8List data)?
    onPlayerRecvAudioSideInfo;
```







