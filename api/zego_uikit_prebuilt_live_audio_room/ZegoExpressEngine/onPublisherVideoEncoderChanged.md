


# onPublisherVideoEncoderChanged property







(void Function([ZegoVideoCodecID](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) fromCodecID, [ZegoVideoCodecID](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) toCodecID, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?) onPublisherVideoEncoderChanged
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the video encoder changes in publishing stream.</p>
<p>Available since: 2.12.0
Description: After the H.265 automatic downgrade policy is enabled, if H.265 encoding is not supported or the encoding fails during the streaming process with H.265 encoding, the SDK will actively downgrade to the specified encoding (H.264), and this callback will be triggered at this time.
When to trigger: In the process of streaming with H.265 encoding, if H.265 encoding is not supported or encoding fails, the SDK will actively downgrade to the specified encoding (H.264), and this callback will be triggered at this time.
Caution: When this callback is triggered, if local video recording or cloud recording is in progress, multiple recording files will be generated. Developers need to collect all the recording files for processing after the recording ends. When this callback is triggered, because the streaming code has changed, the developer can evaluate whether to notify the streaming end, so that the streaming end can deal with it accordingly.</p>
<ul>
<li><code>fromCodecID</code> Video codec ID before the change.</li>
<li><code>toCodecID</code> Video codec ID after the change.</li>
<li><code>channel</code> Publishing stream channel.If you only publish one audio and video stream, you can ignore this parameter.</li>
</ul>



## Implementation

```dart
static void Function(ZegoVideoCodecID fromCodecID, ZegoVideoCodecID toCodecID,
    ZegoPublishChannel channel)? onPublisherVideoEncoderChanged;
```







