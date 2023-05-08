


# onNetworkModeChanged property







(void Function([ZegoNetworkMode](../../zego_uikit_prebuilt_live_audio_room/ZegoNetworkMode.md) mode)?) onNetworkModeChanged
  
_<span class="feature">read / write</span>_



<p>Network mode changed callback.</p>
<p>Available since: 1.20.0
Description: Network mode changed callback.
When to trigger: This callback will be triggered when the device's network mode changed, such as switched from WiFi to 5G, or when network is disconnected.
Restrictions: None.</p>
<ul>
<li><code>mode</code> Current network mode.</li>
</ul>



## Implementation

```dart
static void Function(ZegoNetworkMode mode)? onNetworkModeChanged;
```







