


# onPlayerLowFpsWarning property







(void Function([ZegoVideoCodecID](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) codecID, String streamID)?) onPlayerLowFpsWarning
  
_<span class="feature">read / write</span>_



<p>Playing stream low frame rate warning.</p>
<p>Available since: 2.14.0
Description: This callback triggered by low frame rate when playing stream.
When to trigger: This callback triggered by low frame rate when playing stream.
Caution: If the callback is triggered when the user playing the h.265 stream, you can stop playing the h.265 stream and switch to play the H.264 stream.</p>
<ul>
<li><code>codecID</code> Video codec ID.</li>
<li><code>streamID</code> Stream ID.</li>
</ul>



## Implementation

```dart
static void Function(ZegoVideoCodecID codecID, String streamID)?
    onPlayerLowFpsWarning;
```







