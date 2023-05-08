


# setEffectsBeautyParam method








Future&lt;void> setEffectsBeautyParam
([ZegoEffectsBeautyParam](../../zego_uikit_prebuilt_live_audio_room/ZegoEffectsBeautyParam-class.md) param)





<p>Set beautify param.</p>
<p>Available since: 2.16.0
Description: Set the beauty parameters, including whiten, rosy, smooth, and sharpen.
Use cases: It is often used in scenes such as video calls and live broadcasts.
When to call: You must call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/startEffectsEnv.md">startEffectsEnv</a> to enable the beauty environment before calling this function.
Related APIs: You can call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableEffectsBeauty.md">enableEffectsBeauty</a> to turn on or off the beauty function.
Restrictions: This function only supports Android system 5.0 and above, Android SDK version 21 and above. Calling in publishing or preview is invalid when using the web platform.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>param</code> Beauty option param.</li>
</ul>



## Implementation

```dart
Future<void> setEffectsBeautyParam(ZegoEffectsBeautyParam param) async {
  return await ZegoExpressImpl.instance.setEffectsBeautyParam(param);
}
```







