


# enableHardwareDecoder method








Future&lt;void> enableHardwareDecoder
(bool enable)





<p>Enables or disables hardware decoding.</p>
<p>Available since: 1.1.0
Description: Control whether hardware decoding is used when playing streams, with hardware decoding enabled the SDK will use the GPU for decoding, reducing CPU usage.
Use cases: If developers find that the device heats up badly when playing large resolution audio and video streams during testing on some models, consider calling this function to enable hardware decoding.
Default value: Hardware decoding is disabled by default when this interface is not called.
When to call: This function needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> creates an instance.
Restrictions: None.
Caution: Need to be called before calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/startPlayingStream.md">startPlayingStream</a>, if called after playing the stream, it will only take effect after stopping the stream and re-playing it. Once this configuration has taken effect, it will remain in force until the next call takes effect.</p>
<ul>
<li><code>enable</code> Whether to turn on hardware decoding switch, true: enable hardware decoding, false: disable hardware decoding.</li>
</ul>



## Implementation

```dart
Future<void> enableHardwareDecoder(bool enable) async {
  return await ZegoExpressImpl.instance.enableHardwareDecoder(enable);
}
```







