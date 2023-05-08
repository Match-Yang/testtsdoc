


# startEffectsEnv method








Future&lt;void> startEffectsEnv
()





<p>Enable the Effects beauty environment.</p>
<p>Available since: 2.16.0
Description: Enable the Effects beauty environment. The SDK uses the specified video frame data type for transmission. The Windows platform only supports video frame raw data, the Apple platform only supports CVPixelBuffer, and the Android platform only supports texture2d.
Use cases: It is often used in scenes such as video calls and live broadcasts.
Default value: When this function is not called, the beauty environment is not activated by default.
When to call: Must be called before calling <code>startPreview</code>, <code>startPublishingStream</code>. If you need to modify the configuration, please call <code>logoutRoom</code> to log out of the room first, otherwise it will not take effect.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/enableEffectsBeauty.md">enableEffectsBeauty</a> switch beauty, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess/setEffectsBeautyParam.md">setEffectsBeautyParam</a> set beauty parameters.
Caution: This beauty function is the basic function. If it does not meet the expectations of the developer, you can use the custom video pre-processing function <code>enableCustomVideoProcessing</code> or the custom video capture function <code>enableCustomVideoCapture</code> docking and constructing the AI ​​vision SDK <code>ZegoEffects</code> <a href="https://doc-zh.zego.im/article/9556">https://doc-zh.zego.im/article/9556</a> for best results.
Restrictions: This function only supports Android system 5.0 and above, Android SDK version 21 and above.
Note: This function is only available in ZegoExpressVideo SDK!</p>



## Implementation

```dart
Future<void> startEffectsEnv() async {
  return await ZegoExpressImpl.instance.startEffectsEnv();
}
```







