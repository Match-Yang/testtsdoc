


# enableVirtualStereo method








Future&lt;void> enableVirtualStereo
(bool enable, int angle)





<p>Enable or disable the virtual stereo effect when publishing stream..</p>
<p>Available since: 1.10.0; Note: Starting from 2.15.0, the angle parameter supports setting -1 to present a all round virtual stereo effect.
Description: Call this function to enable / disable the virtual stereo effect when publishing stream.
Use cases: Often used in live broadcasting, voice chatroom and KTV.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Virtual stereo effect is only effective for SDK captured sound.
Caution: You need to set up a dual channel with <code>setAudioConfig</code> for the virtual stereo to take effect.</p>
<ul>
<li><code>enable</code> true to turn on the virtual stereo, false to turn off the virtual stereo.</li>
<li><code>angle</code> The angle of the sound source in virtual stereo in the range of -1 ~ 360, with 90 being directly in front, 0 / 180 / 270 corresponding to the rightmost and leftmost respectively. In particular, when set to -1, it is all round virtual stereo effects.</li>
</ul>



## Implementation

```dart
Future<void> enableVirtualStereo(bool enable, int angle) async {
  return await ZegoExpressImpl.instance.enableVirtualStereo(enable, angle);
}
```







