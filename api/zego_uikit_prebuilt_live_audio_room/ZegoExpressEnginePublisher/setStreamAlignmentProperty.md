


# setStreamAlignmentProperty method








Future&lt;void> setStreamAlignmentProperty
(int alignment, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)





<p>Enable or disable the stream mixing precision alignment function.</p>
<p>Available since: 2.11.0.
Description: Use this interface to enable stream alignment, the SDK will attach network time information to the stream when publishing it for accurate stream alignment.
Use case: Generally used in scenarios such as KTV where stream mixing alignment is required.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution: If mixed flow need time for alignment, the flow through the network push flow need to call startPublishingStream and ZegoPublisherConfig.forceSynchronousNetworkTime = 1, for open network time synchronization.
Related APIs: <code>startMixerTask</code>, <code>startAutoMixerTask</code></p>
<ul>
<li><code>alignment</code> Whether to enable the stream mixing precision alignment function.</li>
<li><code>channel</code> Publish stream channel</li>
</ul>



## Implementation

```dart
Future<void> setStreamAlignmentProperty(
    int alignment, ZegoPublishChannel channel) async {
  return await ZegoExpressImpl.instance
      .setStreamAlignmentProperty(alignment, channel);
}
```







