


# onPlayerStreamEvent property







(void Function([ZegoStreamEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoStreamEvent.md) eventID, String streamID, String extraInfo)?) onPlayerStreamEvent
  
_<span class="feature">read / write</span>_



<p>The callback triggered when playing stream.</p>
<p>Available since: 2.18.0
Description: After start playing stream, this callback will return the current stream address, resource type and protocol-related information.
When to trigger: Play and retry play events.
Caution: None.</p>
<ul>
<li><code>eventID</code> Play stream event ID</li>
<li><code>streamID</code> Stream ID.</li>
<li><code>extraInfo</code> extra info. it is in JSON format. Included information includes "url" for address, "streamProtocol" for stream protocol, including rtmp, flv, avertp, hls, webrtc, etc. "netProtocol" for network protocol, including tcp, udp, quic, "resourceType" for resource type , including cdn, rtc, l3.</li>
</ul>



## Implementation

```dart
static void Function(
        ZegoStreamEvent eventID, String streamID, String extraInfo)?
    onPlayerStreamEvent;
```







