


# onPlayerQualityUpdate property







(void Function(String streamID, [ZegoPlayStreamQuality](../../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality-class.md) quality)?) onPlayerQualityUpdate
  
_<span class="feature">read / write</span>_



<p>Callback for current stream playing quality.</p>
<p>Available since: 1.1.0
Description: After calling the <code>startPlayingStream</code> successfully, this callback will be triggered every 3 seconds. The collection frame rate, bit rate, RTT, packet loss rate and other quality data can be obtained, and the health of the played audio and video streams can be monitored in real time.
Use cases: You can monitor the health of the played audio and video streams in real time according to the quality parameters of the callback function, in order to show the downlink network status on the device UI in real time.
Caution: If you does not know how to use the various parameters of the callback function, you can only focus on the level field of the quality parameter, which is a comprehensive value describing the downlink network calculated by SDK based on the quality parameters.
Related callbacks: After calling the <code>startPublishingStream</code> successfully, a callback <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherQualityUpdate.md">onPublisherQualityUpdate</a> will be received every 3 seconds. You can monitor the health of publish streams in real time based on quality data such as frame rate, code rate, RTT, packet loss rate, etc.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>quality</code> Playing stream quality, including audio and video framerate, bitrate, RTT, etc.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, ZegoPlayStreamQuality quality)?
    onPlayerQualityUpdate;
```







