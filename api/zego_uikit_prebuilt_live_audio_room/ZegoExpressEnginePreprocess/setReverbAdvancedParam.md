


# setReverbAdvancedParam method








Future&lt;void> setReverbAdvancedParam
([ZegoReverbAdvancedParam](../../zego_uikit_prebuilt_live_audio_room/ZegoReverbAdvancedParam-class.md) param)





<p>Setting up the specific reverberation parameters.</p>
<p>Available since: 1.10.0
Description: Call this function to set preset reverb effect.
Use cases: Often used in live broadcasting, voice chatroom and KTV.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Reverb effect is only effective for SDK captured sound.
Caution: Different values dynamically set during publishing stream will take effect. When all parameters are set to 0, the reverberation is turned off.
Related APIs:
<a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbPreset.md">setReverbPreset</a> provide a set of preset reverb effects.
If you need advanced reverb/echo/voice changer effect, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbAdvancedParam.md">setReverbAdvancedParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbEchoParam.md">setReverbEchoParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerParam.md">setVoiceChangerParam</a> together.</p>
<ul>
<li><code>param</code> Reverb advanced parameter.</li>
</ul>



## Implementation

```dart
Future<void> setReverbAdvancedParam(ZegoReverbAdvancedParam param) async {
  return await ZegoExpressImpl.instance.setReverbAdvancedParam(param);
}
```







