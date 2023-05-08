


# setVoiceChangerParam method








Future&lt;void> setVoiceChangerParam
([ZegoVoiceChangerParam](../../zego_uikit_prebuilt_live_audio_room/ZegoVoiceChangerParam-class.md) param)





<p>Setting up the specific voice changer parameters.</p>
<p>Available since: 1.10.0
Description: Call this function to set custom voice changer effect.
Use cases: Often used in live broadcasting, voice chatroom and KTV.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Voice changer effect is only effective for SDK captured sound.
Related APIs:
<a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerPreset.md">setVoiceChangerPreset</a> provide a set of preset voice changer effects.
If you need advanced reverb/echo/voice changer effect, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbAdvancedParam.md">setReverbAdvancedParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbEchoParam.md">setReverbEchoParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerParam.md">setVoiceChangerParam</a> together.</p>
<ul>
<li><code>param</code> Voice changer parameters.</li>
</ul>



## Implementation

```dart
Future<void> setVoiceChangerParam(ZegoVoiceChangerParam param) async {
  return await ZegoExpressImpl.instance.setVoiceChangerParam(param);
}
```







