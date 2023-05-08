


# onPublisherCapturedVideoFirstFrame property







(void Function([ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?) onPublisherCapturedVideoFirstFrame
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the first video frame is captured.</p>
<p>Available since: 1.1.0
Description: After the <code>startPublishingStream</code> function is called successfully, this callback will be called when SDK received the first frame of video data. Developers can use this callback to determine whether SDK has actually collected video data. If the callback is not received, the video capture device is occupied or abnormal.
Trigger: In the case of no startPublishingStream video stream or preview, the first startPublishingStream video stream or first preview, that is, when the engine of the audio and video module inside SDK starts, it will collect video data of the local device and receive this callback.
Related callbacks: After the <code>startPublishingStream</code> function is called successfully, determine if the SDK actually collected audio data by the callback function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherCapturedAudioFirstFrame.md">onPublisherCapturedAudioFirstFrame</a>, determine if the SDK has rendered the first frame of video data collected by calling back <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherRenderVideoFirstFrame.md">onPublisherRenderVideoFirstFrame</a>.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>channel</code> Publishing stream channel.If you only publish one audio and video stream, you can ignore this parameter.</li>
</ul>



## Implementation

```dart
static void Function(ZegoPublishChannel channel)?
    onPublisherCapturedVideoFirstFrame;
```







