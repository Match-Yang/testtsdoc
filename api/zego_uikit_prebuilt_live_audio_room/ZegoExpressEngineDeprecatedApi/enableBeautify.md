


# enableBeautify method







- @Deprecated(&#39;Deprecated since 2.16.0, please use the [enableEffectsBeauty] function instead.&#39;)

Future&lt;void> ~~enableBeautify~~
(int featureBitmask, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p><code>Deprecated</code> Enables or disables the beauty features for the specified publish channel. Deprecated since 2.16.0, please use the <code>enableEffectsBeauty</code> function instead.</p>
<p>Available since: 1.1.0
Description: When developers do not have much need for beauty features, they can use this function to set some very simple beauty effects.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Default value: When this function is not called, the beauty feature is not enabled by default.
Related APIs: After turning on the beauty features, you can call the <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDeprecatedApi/setBeautifyOption.md">setBeautifyOption</a> function to adjust the beauty parameters.
Caution: This beauty feature is very simple and may not meet the developer’s expectations. It is recommended to use the custom video processing function <code>enableCustomVideoProcessing</code> or the custom video capture function <code>enableCustomVideoCapture</code> to connect the <code>ZegoEffects</code> AI SDK <a href="https://docs.zegocloud.com/article/9896">https://docs.zegocloud.com/article/9896</a> for best results.
Restrictions: In the case of using the custom video capture function, since the developer has handle the video data capturing, the SDK is no longer responsible for the video data capturing, so this function is no longer valid. It is also invalid when using the custom video processing function.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<p>@deprecated Deprecated since 2.16.0, please use the <code>enableEffectsBeauty</code> function instead.</p>
<ul>
<li><code>featureBitmask</code> Beauty features, bitmask format, you can choose to enable several features in <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoBeautifyFeature-class.md">ZegoBeautifyFeature</a> at the same time</li>
<li><code>channel</code> Publishing stream channel</li>
</ul>



## Implementation

```dart
@Deprecated(
    'Deprecated since 2.16.0, please use the [enableEffectsBeauty] function instead.')
Future<void> enableBeautify(int featureBitmask,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .enableBeautify(featureBitmask, channel: channel);
}
```







