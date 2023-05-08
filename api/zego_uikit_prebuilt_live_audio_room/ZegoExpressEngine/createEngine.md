


# createEngine method







- @Deprecated(&#39;Deprecated since 2.14.0, please use the method with the same name without [isTestEnv] parameter instead.&#39;)

Future&lt;void> ~~createEngine~~
(int appID, String appSign, bool isTestEnv, [ZegoScenario](../../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) scenario, {bool? enablePlatformView})





<p><code>Deprecated</code> Create ZegoExpressEngine singleton object and initialize SDK. Deprecated since 2.14.0, please use the method with the same name without <code>isTestEnv</code> parameter instead. Please refer to <a href="https://docs.zegocloud.com/article/13315">Testing environment deprecation</a> for more details.</p>
<p>Available: 1.1.0 ~ 2.13.1, deprecated since 2.14.0, please use the method with the same name without <code>isTestEnv</code> parameter instead
Description: Create ZegoExpressEngine singleton object and initialize SDK.
When to call: The engine needs to be created before calling other functions.
Restrictions: None.
Caution: The SDK only supports the creation of one instance of ZegoExpressEngine. Multiple calls to this function return the same object.</p>
<p>@deprecated Deprecated since 2.14.0, please use the method with the same name without <code>isTestEnv</code> parameter instead.</p>
<ul>
<li><code>appID</code> Application ID issued by ZEGO for developers, please apply from the ZEGO Admin Console <a href="https://console.zegocloud.com">https://console.zegocloud.com</a> The value ranges from 0 to 4294967295.</li>
<li><code>appSign</code> Application signature for each AppID, please apply from the ZEGO Admin Console. Application signature is a 64 character string. Each character has a range of '0' ~ '9', 'a' ~ 'z'. AppSign 2.17.0 and later allows null or no transmission. If the token is passed empty or not passed, the token must be entered in the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig-class.md">ZegoRoomConfig</a> parameter for authentication when the <code>loginRoom</code> interface is called to login to the room.</li>
<li><code>isTestEnv</code> <code>Deprecated</code> For providing better and more standardized services, starting from 2021-11-16, ZEGO no longer classifies environments into production environments and testing environments. f you create your project in ZEGO Admin Console on/before 2021-11-16, refer to <a href="https://docs.zegocloud.com/article/13315">Testing environment deprecation</a> to upgrade the SDK and adjust related codes.</li>
<li><code>scenario</code> The room scenario. the SDK will optimize the audio and video configuration for the specified scenario to achieve the best effect in this scenario. After specifying the scenario, you can call other APIs to adjusting the audio and video configuration. Differences between scenarios and how to choose a suitable scenario, please refer to <a href="https://docs.zegocloud.com/article/14940">https://docs.zegocloud.com/article/14940</a></li>
<li><code>enablePlatformView</code> Set whether to use Platform View for rendering, true: rendering using Platform View, false: rendering using Texture, default is false. Currently the web platform only supports rendering with Platform View. When using the <code>createCanvasView</code> interface, If the preferred render mode is not supported, another render mode is automatically used.</li>
</ul>



## Implementation

```dart
@Deprecated(
    'Deprecated since 2.14.0, please use the method with the same name without [isTestEnv] parameter instead.')
static Future<void> createEngine(
    int appID, String appSign, bool isTestEnv, ZegoScenario scenario,
    {bool? enablePlatformView}) async {
  return await ZegoExpressImpl.createEngine(
      appID, appSign, isTestEnv, scenario,
      enablePlatformView: enablePlatformView);
}
```







