


# onPublisherStateUpdate property







(void Function(String streamID, [ZegoPublisherState](../../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md) state, int errorCode, Map&lt;String, dynamic> extendedData)?) onPublisherStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the state of stream publishing changes.</p>
<p>Available since: 1.1.0
Description: After calling the <code>startPublishingStream</code> successfully, the notification of the publish stream state change can be obtained through the callback function. You can roughly judge the user's uplink network status based on whether the state parameter is in <code>PUBLISH_REQUESTING</code>.
Caution: The parameter <code>extendedData</code> is extended information with state updates. If you use ZEGO's CDN content distribution network, after the stream is successfully published, the keys of the content of this parameter are <code>flv_url_list</code>, <code>rtmp_url_list</code>, <code>hls_url_list</code>, these correspond to the publishing stream URLs of the flv, rtmp, and hls protocols.
Related callbacks: After calling the <code>startPlayingStream</code> successfully, the notification of the play stream state change can be obtained through the callback function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerStateUpdate.md">onPlayerStateUpdate</a>. You can roughly judge the user's downlink network status based on whether the state parameter is in <code>PLAY_REQUESTING</code>.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>state</code> State of publishing stream.</li>
<li><code>errorCode</code> The error code corresponding to the status change of the publish stream, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
<li><code>extendedData</code> Extended information with state updates, include playing stream CDN address.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, ZegoPublisherState state, int errorCode,
    Map<String, dynamic> extendedData)? onPublisherStateUpdate;
```







