


# enablePlayStreamVirtualStereo method








Future&lt;void> enablePlayStreamVirtualStereo
(bool enable, int angle, String streamID)





<p>Enable or disable the virtual stereo effect when playing stream.</p>
<p>Available since: 2.8.0
Description: Call this function to enable/disable the virtual stereo effect when playing stream.
Use cases: Often used in live broadcasting, voice chatroom and KTV.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution: It can dynamically switch and set angle parameters before and after playing stream. After stopping playing stream, it will automatically reset and disable.</p>
<ul>
<li><code>enable</code> true to turn on the virtual stereo, false to turn off the virtual stereo.</li>
<li><code>angle</code> The angle of the sound source in virtual stereo in the range of 0 ~ 360, with 90 being directly in front, 0 / 180 / 270 corresponding to the rightmost and leftmost respectively.</li>
<li><code>streamID</code> Stream ID.</li>
</ul>



## Implementation

```dart
Future<void> enablePlayStreamVirtualStereo(
    bool enable, int angle, String streamID) async {
  return await ZegoExpressImpl.instance
      .enablePlayStreamVirtualStereo(enable, angle, streamID);
}
```







