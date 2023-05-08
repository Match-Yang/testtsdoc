


# onPublisherRenderVideoFirstFrame property







(void Function([ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?) onPublisherRenderVideoFirstFrame
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the first video frame is rendered.</p>
<p>Available since: 2.4.0
Description: this callback will be called after SDK rendered the first frame of video data captured. This interface is for preview rendering. The first frame callback is only available for external collection and internal preview. If it is not for SDK rendering, there is no such callback.
Related callbacks: After the <code>startPublishingStream</code> function is called successfully, determine if the SDK actually collected audio data by the callback function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherCapturedAudioFirstFrame.md">onPublisherCapturedAudioFirstFrame</a>, determine if the SDK actually collected video data by the callback function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherCapturedVideoFirstFrame.md">onPublisherCapturedVideoFirstFrame</a>.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>channel</code> Publishing stream channel.If you only publish one audio and video stream, you can ignore this parameter.</li>
</ul>



## Implementation

```dart
static void Function(ZegoPublishChannel channel)?
    onPublisherRenderVideoFirstFrame;
```







