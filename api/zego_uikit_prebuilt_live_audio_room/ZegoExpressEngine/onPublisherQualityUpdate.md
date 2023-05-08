


# onPublisherQualityUpdate property







(void Function(String streamID, [ZegoPublishStreamQuality](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishStreamQuality-class.md) quality)?) onPublisherQualityUpdate
  
_<span class="feature">read / write</span>_



<p>Callback for current stream publishing quality.</p>
<p>Available since: 1.1.0
Description: After calling the <code>startPublishingStream</code> successfully, the callback will be received every 3 seconds default(If you need to change the time, please contact the instant technical support to configure). Through the callback, the collection frame rate, bit rate, RTT, packet loss rate and other quality data of the published audio and video stream can be obtained, and the health of the publish stream can be monitored in real time.You can monitor the health of the published audio and video streams in real time according to the quality parameters of the callback function, in order to show the uplink network status in real time on the device UI.
Caution: If you does not know how to use the parameters of this callback function, you can only pay attention to the <code>level</code> field of the <code>quality</code> parameter, which is a comprehensive value describing the uplink network calculated by SDK based on the quality parameters.
Related callbacks: After calling the <code>startPlayingStream</code> successfully, the callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerQualityUpdate.md">onPlayerQualityUpdate</a> will be received every 3 seconds. You can monitor the health of play streams in real time based on quality data such as frame rate, code rate, RTT, packet loss rate, etc.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>quality</code> Publishing stream quality, including audio and video framerate, bitrate, RTT, etc.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, ZegoPublishStreamQuality quality)?
    onPublisherQualityUpdate;
```







