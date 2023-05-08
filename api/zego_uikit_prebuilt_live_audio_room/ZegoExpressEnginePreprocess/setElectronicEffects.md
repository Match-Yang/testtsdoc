


# setElectronicEffects method








Future&lt;void> setElectronicEffects
(bool enable, [ZegoElectronicEffectsMode](../../zego_uikit_prebuilt_live_audio_room/ZegoElectronicEffectsMode.md) mode, int tonal)





<p>Turn on or off the electronic sound effect.</p>
<p>Available since: 2.13.0
Description: Call this function to turn on or off the electronic sound effect.
Use cases: Often used in live broadcasting, voice chatroom and sung unaccompanied scenes.
Default value: When this function is not called, the electronic sound effect is not enabled by default.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Caution: When the mode parameter is Harmonic Minor, the tonal parameter does not take effect.
Related APIs: Common electronic sound effect configurations can be set via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerPreset.md">setVoiceChangerPreset</a>.</p>
<ul>
<li><code>enable</code> true to turn on the electronic sound effect, false to turn off the electronic sound effect.</li>
<li><code>mode</code> Mode of Electronic Effects reference.</li>
<li><code>tonal</code> The starting pitch of an electric tone in a given mode, representing 12 semitones in one octave of the sound, in the range <code>0, 11</code>.</li>
</ul>



## Implementation

```dart
Future<void> setElectronicEffects(
    bool enable, ZegoElectronicEffectsMode mode, int tonal) async {
  return await ZegoExpressImpl.instance
      .setElectronicEffects(enable, mode, tonal);
}
```







