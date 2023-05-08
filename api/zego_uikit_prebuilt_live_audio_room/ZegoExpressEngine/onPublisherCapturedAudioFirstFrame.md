


# onPublisherCapturedAudioFirstFrame property







(void Function()?) onPublisherCapturedAudioFirstFrame
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the first audio frame is captured.</p>
<p>Available since: 1.1.0
Description: After the <code>startPublishingStream</code> function is called successfully, this callback will be called when SDK received the first frame of audio data. Developers can use this callback to determine whether SDK has actually collected audio data. If the callback is not received, the audio capture device is occupied or abnormal.
Trigger: In the case of no startPublishingStream audio and video stream or preview <code>startPreview</code>, the first startPublishingStream audio and video stream or first preview, that is, when the engine of the audio and video module inside SDK starts, it will collect audio data of the local device and receive this callback.
Related callbacks: After the <code>startPublishingStream</code> function is called successfully, determine if the SDK actually collected video data by the callback function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherCapturedVideoFirstFrame.md">onPublisherCapturedVideoFirstFrame</a>, determine if the SDK has rendered the first frame of video data collected by calling back <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherRenderVideoFirstFrame.md">onPublisherRenderVideoFirstFrame</a>.</p>



## Implementation

```dart
static void Function()? onPublisherCapturedAudioFirstFrame;
```







