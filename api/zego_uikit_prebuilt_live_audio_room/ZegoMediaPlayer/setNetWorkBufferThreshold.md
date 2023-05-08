


# setNetWorkBufferThreshold method








Future&lt;void> setNetWorkBufferThreshold
(int threshold)





<p>Use this interface to set the cache threshold that the media player needs to resume playback. The SDK default value is 5000ms，The valid value is greater than or equal to 1000ms</p>
<p>The setting must be called before loading the resource, and it will take effect during the entire life cycle of the media player.
When the network status is poor and the media player has finished playing the cached network resources, it will stop playing, and notify the user through the <code>ZegoMediaPlayerNetworkEvent.BUFFER_BEGIN</code> state of the callback interface <code>onMediaPlayerNetworkEvent</code> that the network resources are being recached.
Only when the cached network resources are greater than the set threshold, the media player will automatically resume playback at the original paused position, and notify the user through the <code>ZegoMediaPlayerNetworkEvent.BUFFER_ENDED</code> of the callback interface <code>onMediaPlayerNetworkEvent</code> that the user has cached the network resources The threshold was reached and playback resumed.</p>
<ul>
<li><code>threshold</code> Threshold that needs to be reached to resume playback, unit ms.</li>
</ul>



## Implementation

```dart
Future<void> setNetWorkBufferThreshold(int threshold);
```







