


# setReverbEchoParam method








Future&lt;void> setReverbEchoParam
([ZegoReverbEchoParam](../../zego_uikit_prebuilt_live_audio_room/ZegoReverbEchoParam-class.md) param)





<p>Setting up the specific reverberation echo parameters.</p>
<p>Available since: 1.17.0
Description: Call this function to set reverb echo effect. This function can be used with voice changer and reverb to achieve a variety of custom sound effects.
Use cases: Often used in live broadcasting, voice chatroom and KTV.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Reverb echo effect is only effective for SDK captured sound.
Related APIs: If you need advanced reverb/echo/voice changer effect, please use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbAdvancedParam.md">setReverbAdvancedParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setReverbEchoParam.md">setReverbEchoParam</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setVoiceChangerParam.md">setVoiceChangerParam</a> together.</p>
<ul>
<li><code>param</code> The reverberation echo parameter.</li>
</ul>



## Implementation

```dart
Future<void> setReverbEchoParam(ZegoReverbEchoParam param) async {
  return await ZegoExpressImpl.instance.setReverbEchoParam(param);
}
```







