


# setPlayStreamBufferIntervalRange method








Future&lt;void> setPlayStreamBufferIntervalRange
(String streamID, int minBufferInterval, int maxBufferInterval)





<p>Set the adaptive adjustment interval range of the buffer for playing stream.</p>
<p>Available since: 2.1.0
Description: Set the range of adaptive adjustment of the internal buffer of the sdk when streaming is 0-4000ms.
Use cases: Generally, in the case of a poor network environment, adjusting and increasing the playback buffer of the pull stream will significantly reduce the audio and video freezes, but will increase the delay.
When to call: after called <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Caution: When the upper limit of the cache interval set by the developer exceeds 4000ms, the value will be 4000ms. When the upper limit of the cache interval set by the developer is less than the lower limit of the cache interval, the upper limit will be automatically set as the lower limit.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>minBufferInterval</code> The lower limit of the buffer adaptation interval, in milliseconds. The default value is 0ms.</li>
<li><code>maxBufferInterval</code> The upper limit of the buffer adaptation interval, in milliseconds. The default value is 4000ms.</li>
</ul>



## Implementation

```dart
Future<void> setPlayStreamBufferIntervalRange(
    String streamID, int minBufferInterval, int maxBufferInterval) async {
  return await ZegoExpressImpl.instance.setPlayStreamBufferIntervalRange(
      streamID, minBufferInterval, maxBufferInterval);
}
```







