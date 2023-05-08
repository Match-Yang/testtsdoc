


# onPlayerVideoSizeChanged property







(void Function(String streamID, int width, int height)?) onPlayerVideoSizeChanged
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the stream playback resolution changes.</p>
<p>Available since: 1.1.0
Description: After the <code>startPlayingStream</code> function is called successfully, the play resolution will change when the first frame of video data is received, or when the publisher changes the encoding resolution by calling <code>setVideoConfig</code>, or when the network traffic control strategies work.
Use cases: Developers can update or switch the UI components that actually play the stream based on the final resolution of the stream.
Trigger: After the <code>startPlayingStream</code> function is called successfully, this callback is triggered when the video resolution changes while playing the stream.
Caution: If the stream is only audio data, the callback will not be triggered.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>width</code> Video decoding resolution width.</li>
<li><code>height</code> Video decoding resolution height.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, int width, int height)?
    onPlayerVideoSizeChanged;
```







