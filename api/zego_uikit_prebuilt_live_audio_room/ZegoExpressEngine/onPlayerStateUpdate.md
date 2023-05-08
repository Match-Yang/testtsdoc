


# onPlayerStateUpdate property







(void Function(String streamID, [ZegoPlayerState](../../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md) state, int errorCode, Map&lt;String, dynamic> extendedData)?) onPlayerStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the state of stream playing changes.</p>
<p>Available since: 1.1.0
Description: After calling the <code>startPlayingStream</code> successfully, the notification of the playing stream state change can be obtained through the callback function. You can roughly judge the user's downlink network status based on whether the state parameter is in <code>PLAY_REQUESTING</code>.
When to trigger:  After calling the <code>startPublishingStream</code>, this callback is triggered when a playing stream's state changed.
Related callbacks: After calling the <code>startPublishingStream</code> successfully, the notification of the publish stream state change can be obtained through the callback function <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherStateUpdate.md">onPublisherStateUpdate</a>. You can roughly judge the user's uplink network status based on whether the state parameter is in <code>PUBLISH_REQUESTING</code>.</p>
<ul>
<li><code>streamID</code> stream ID.</li>
<li><code>state</code> State of playing stream.</li>
<li><code>errorCode</code> The error code corresponding to the status change of the playing stream, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
<li><code>extendedData</code> Extended Information with state updates. As the standby, only an empty json table is currently returned.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, ZegoPlayerState state, int errorCode,
    Map<String, dynamic> extendedData)? onPlayerStateUpdate;
```







