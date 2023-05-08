


# onMediaPlayerNetworkEvent property







(void Function([ZegoMediaPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, [ZegoMediaPlayerNetworkEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerNetworkEvent.md) networkEvent)?) onMediaPlayerNetworkEvent
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the network status of the media player changes.</p>
<p>Available since: 1.3.4
Description: The callback triggered when the network status of the media player changes.
Trigger: When the media player is playing network resources, this callback will be triggered when the status change of the cached data.
Restrictions: The callback will only be triggered when the network resource is played.
Related APIs: <code>setNetWorkBufferThreshold</code>.</p>
<ul>
<li><code>mediaPlayer</code> Callback player object.</li>
<li><code>networkEvent</code> Network status event.</li>
</ul>



## Implementation

```dart
static void Function(ZegoMediaPlayer mediaPlayer,
    ZegoMediaPlayerNetworkEvent networkEvent)? onMediaPlayerNetworkEvent;
```







