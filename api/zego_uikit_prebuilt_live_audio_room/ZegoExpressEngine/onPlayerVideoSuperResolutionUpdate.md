


# onPlayerVideoSuperResolutionUpdate property







(void Function(String streamID, [ZegoSuperResolutionState](../../zego_uikit_prebuilt_live_audio_room/ZegoSuperResolutionState.md) state, int errorCode)?) onPlayerVideoSuperResolutionUpdate
  
_<span class="feature">read / write</span>_



<p>Playing stream video super resolution enabled state changes.</p>
<p>Available since: 3.0.0
Description: Playing stream video super resolution enabled state changes.
When to trigger: When <code>enableVideoSuperResolution</code> enables or disables video super resolution, the developer will be notified whether to enable video super resolution according to the actual situation when playing stream video rendering.
Caution: None.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>state</code> Video super resolution state.</li>
<li><code>errorCode</code> Error code, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
</ul>



## Implementation

```dart
static void Function(
        String streamID, ZegoSuperResolutionState state, int errorCode)?
    onPlayerVideoSuperResolutionUpdate;
```







