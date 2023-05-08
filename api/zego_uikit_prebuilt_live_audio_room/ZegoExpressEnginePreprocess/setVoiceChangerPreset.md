


# setVoiceChangerPreset method








Future&lt;void> setVoiceChangerPreset
([ZegoVoiceChangerPreset](../../zego_uikit_prebuilt_live_audio_room/ZegoVoiceChangerPreset.md) preset)





<p>Setting up the voice changer via preset enumeration.</p>
<p>Available since: 1.17.0
Description: Call this function to use preset voice changer effect.
Use cases: Often used in live broadcasting, voice chatroom and KTV.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Voice changer effect is only effective for SDK captured sound.
Related APIs:
If you need advanced voice changer effect, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerParam.md">setVoiceChangerParam</a>.
The effect of using this function together with <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbPreset.md">setReverbPreset</a> may be different from what is expected. If you need to use it at the same time, it is recommended to enable the voice changer first, and then enable the reverb.
Using ANDROID/ETHEREAL preset voice changer effect will modify reverberation or reverberation echo parameters. Calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerParam.md">setVoiceChangerParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbAdvancedParam.md">setReverbAdvancedParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbEchoParam.md">setReverbEchoParam</a> may affect the voice changer effect after use these preset voice changer effect.
If you need advanced reverb/echo/electronic effects/voice changer effect, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbAdvancedParam.md">setReverbAdvancedParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbEchoParam.md">setReverbEchoParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setElectronicEffects.md">setElectronicEffects</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerParam.md">setVoiceChangerParam</a> together.</p>
<ul>
<li><code>preset</code> The voice changer preset enumeration.</li>
</ul>



## Implementation

```dart
Future<void> setVoiceChangerPreset(ZegoVoiceChangerPreset preset) async {
  return await ZegoExpressImpl.instance.setVoiceChangerPreset(preset);
}
```







