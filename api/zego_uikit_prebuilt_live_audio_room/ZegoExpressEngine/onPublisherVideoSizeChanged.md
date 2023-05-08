


# onPublisherVideoSizeChanged property







(void Function(int width, int height, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?) onPublisherVideoSizeChanged
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the video capture resolution changes.</p>
<p>Available since: 1.1.0
Description: When the audio and video stream is not published <code>startPublishingStream</code> or previewed <code>startPreview</code> for the first time, the publishing stream or preview first time, that is, the engine of the audio and video module inside the SDK is started, the video data of the local device will be collected, and the collection resolution will change at this time.
Trigger: After the successful publish <code>startPublishingStream</code>, the callback will be received if there is a change in the video capture resolution in the process of publishing the stream.
Use cases: You can use this callback to remove the cover of the local preview UI and similar operations.You can also dynamically adjust the scale of the preview view based on the resolution of the callback.
Caution: What is notified during external collection is the change in encoding resolution, which will be affected by flow control.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>width</code> Video capture resolution width.</li>
<li><code>height</code> Video capture resolution height.</li>
<li><code>channel</code> Publishing stream channel.If you only publish one audio and video stream, you can ignore this parameter.</li>
</ul>



## Implementation

```dart
static void Function(int width, int height, ZegoPublishChannel channel)?
    onPublisherVideoSizeChanged;
```







