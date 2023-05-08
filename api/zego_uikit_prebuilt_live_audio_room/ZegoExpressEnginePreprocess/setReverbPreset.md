


# setReverbPreset method








Future&lt;void> setReverbPreset
([ZegoReverbPreset](../../zego_uikit_prebuilt_live_audio_room/ZegoReverbPreset.md) preset)





<p>Setting up the reverberation via preset enumeration.</p>
<p>Available since: 1.17.0
Description: Call this function to set preset reverb effect.
Use cases: Often used in live broadcasting, voice chatroom and KTV.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>. Support call this function to change preset reverb effect during publishing stream.
Restrictions: Reverb effect is only effective for SDK captured sound.
Related APIs:
If you need advanced reverb effect, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbAdvancedParam.md">setReverbAdvancedParam</a>.
The effect of using this function together with <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerPreset.md">setVoiceChangerPreset</a> may be different from what is expected. If you need to use it at the same time, it is recommended to enable the voice changer first, and then enable the reverb.
If you need advanced reverb/echo/voice changer effect, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbAdvancedParam.md">setReverbAdvancedParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbEchoParam.md">setReverbEchoParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerParam.md">setVoiceChangerParam</a> together.</p>
<ul>
<li><code>preset</code> The reverberation preset enumeration.</li>
</ul>



## Implementation

```dart
Future<void> setReverbPreset(ZegoReverbPreset preset) async {
  return await ZegoExpressImpl.instance.setReverbPreset(preset);
}
```







