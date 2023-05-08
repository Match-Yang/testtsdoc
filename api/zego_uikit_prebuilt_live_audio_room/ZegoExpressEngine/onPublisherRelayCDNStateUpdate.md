


# onPublisherRelayCDNStateUpdate property







(void Function(String streamID, List&lt;[ZegoStreamRelayCDNInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoStreamRelayCDNInfo-class.md)> infoList)?) onPublisherRelayCDNStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the state of relayed streaming to CDN changes.</p>
<p>Available since: 1.1.0
Description: Developers can use this callback to determine whether the audio and video streams of the relay CDN are normal. If they are abnormal, further locate the cause of the abnormal audio and video streams of the relay CDN and make corresponding disaster recovery strategies.
Trigger: After the ZEGO RTC server relays the audio and video streams to the CDN, this callback will be received if the CDN relay status changes, such as a stop or a retry.
Caution: If you do not understand the cause of the abnormality, you can contact ZEGO technicians to analyze the specific cause of the abnormality.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>infoList</code> List of information that the current CDN is relaying.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, List<ZegoStreamRelayCDNInfo> infoList)?
    onPublisherRelayCDNStateUpdate;
```







