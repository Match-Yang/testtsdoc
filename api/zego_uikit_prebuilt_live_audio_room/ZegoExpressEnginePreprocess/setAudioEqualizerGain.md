


# setAudioEqualizerGain method








Future&lt;void> setAudioEqualizerGain
(int bandIndex, double bandGain)





<p>Set the sound equalizer (EQ).</p>
<p>Available since: 1.12.0
Description: Call this function to set the sound equalizer adjust the tone.
Use cases: Often used in voice chatroom, KTV.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.</p>
<ul>
<li><code>bandIndex</code> Band frequency index, the value range is <code>0, 9</code>, corresponding to 10 frequency bands, and the center frequencies are <code>31, 62, 125, 250, 500, 1K, 2K, 4K, 8K, 16K</code> Hz.</li>
<li><code>bandGain</code> Band gain for the index, the value range is <code>-15, 15</code>. Default value is 0, if all gain values in all frequency bands are 0, EQ function will be disabled.</li>
</ul>



## Implementation

```dart
Future<void> setAudioEqualizerGain(int bandIndex, double bandGain) async {
  return await ZegoExpressImpl.instance
      .setAudioEqualizerGain(bandIndex, bandGain);
}
```







