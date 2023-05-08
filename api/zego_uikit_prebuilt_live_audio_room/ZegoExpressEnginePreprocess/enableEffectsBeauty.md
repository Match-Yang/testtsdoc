


# enableEffectsBeauty method








Future&lt;void> enableEffectsBeauty
(bool enable)





<p>Enables or disables the beauty effect.</p>
<p>Available since: 2.16.0
Description: Support basic beauty functions, including whiten, rosy, smooth, and sharpen.
Use cases: It is often used in scenes such as video calls and live broadcasts.
When to call: You must call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/startEffectsEnv.md">startEffectsEnv</a> to enable the beauty environment before calling this function.
Default value: When this function is not called, the beauty effect is not enabled by default.
Related APIs: You can call the <code>setBeautifyOption</code> function to adjust the beauty parameters.
Caution: This beauty function is the basic function. If it does not meet the expectations of the developer, you can use the custom video pre-processing function <code>enableCustomVideoProcessing</code> or the custom video capture function <code>enableCustomVideoCapture</code> docking and constructing the AI ​​vision SDK <code>ZegoEffects</code> for best results.
Restrictions: If this function is used on the Android platform, it only supports 5.0 and above, SDK version 21 and above. Calling in publishing or preview is invalid when using the web platform.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>enable</code> Whether to enable the beauty effect, true is enabled; false is disabled, and the default is false.</li>
</ul>



## Implementation

```dart
Future<void> enableEffectsBeauty(bool enable) async {
  return await ZegoExpressImpl.instance.enableEffectsBeauty(enable);
}
```







