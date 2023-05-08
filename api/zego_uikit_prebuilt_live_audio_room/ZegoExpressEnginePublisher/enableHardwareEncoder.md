


# enableHardwareEncoder method








Future&lt;void> enableHardwareEncoder
(bool enable)





<p>Enables or disables hardware encoding.</p>
<p>Available since: 1.1.0
Description: Whether to use the hardware encoding function when publishing the stream, the GPU is used to encode the stream and to reduce the CPU usage.
When to call: The setting can take effect before the stream published. If it is set after the stream published, the stream should be stopped first before it takes effect.
Caution: Because hard-coded support is not particularly good for a few models, SDK uses software encoding by default. If the developer finds that the device is hot when publishing a high-resolution audio and video stream during testing of some models, you can consider calling this function to enable hard coding.</p>
<ul>
<li><code>enable</code> Whether to enable hardware encoding, true: enable hardware encoding, false: disable hardware encoding.</li>
</ul>



## Implementation

```dart
Future<void> enableHardwareEncoder(bool enable) async {
  return await ZegoExpressImpl.instance.enableHardwareEncoder(enable);
}
```







