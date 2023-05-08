


# onPublisherStreamEvent property







(void Function([ZegoStreamEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoStreamEvent.md) eventID, String streamID, String extraInfo)?) onPublisherStreamEvent
  
_<span class="feature">read / write</span>_



<p>The callback triggered when publishing stream.</p>
<p>Available since: 2.18.0
Description: After start publishing stream, this callback will return the current stream address, resource type and protocol-related information.
When to trigger: Publish and retry publish events.
Caution: None.</p>
<ul>
<li><code>eventID</code> Publish stream event ID</li>
<li><code>streamID</code> Stream ID.</li>
<li><code>extraInfo</code> extra info. it is in JSON format. Included information includes "url" for address, "streamProtocol" for stream protocol, including rtmp, flv, avertp, hls, webrtc, etc. "netProtocol" for network protocol, including tcp, udp, quic, "resourceType" for resource type , including cdn, rtc, l3.</li>
</ul>



## Implementation

```dart
static void Function(
        ZegoStreamEvent eventID, String streamID, String extraInfo)?
    onPublisherStreamEvent;
```







