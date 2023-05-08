


# onPlayerRenderCameraVideoFirstFrame property







(void Function(String streamID)?) onPlayerRenderCameraVideoFirstFrame
  
_<span class="feature">read / write</span>_



<p>Calls back when the stream playing end renders the first frame of the video from the remote camera.</p>
<p>Available since: 3.0.0
Description: After calling the <code>startPlayingStream</code> function to pull the stream successfully, the SDK will receive this callback after pulling the stream and rendering the first frame of remote camera video data.
Use cases: Developer can use this callback to count time consuming that take the first frame time or update the UI for playing stream.
Trigger: After the remote <code>enableCamera</code> enables the camera, or after <code>mutePublishStreamVideo</code> is true and starts to send video data, the SDK will receive this callback after playing the stream and rendering the first frame of the remote camera video data.
Caution: It is only applicable when the remote end uses the camera to push the stream. Only applicable to RTC publishing and playing streaming scenarios.
Related callbacks: After a successful call to <code>startPlayingStream</code>, the callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRecvVideoFirstFrame.md">onPlayerRecvVideoFirstFrame</a> determines whether the SDK has received the video data.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
</ul>



## Implementation

```dart
static void Function(String streamID)? onPlayerRenderCameraVideoFirstFrame;
```







