


# setBeautifyOption method







- @Deprecated(&#39;Deprecated since 2.16.0, please use the [setEffectsBeautyParam] function instead.&#39;)

Future&lt;void> ~~setBeautifyOption~~
([ZegoBeautifyOption](../../zego_uikit_prebuilt_live_audio_room/ZegoBeautifyOption-class.md) option, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p><code>Deprecated</code> Set beautify option. Deprecated since 2.16.0, please use the <code>setEffectsBeautyParam</code> function instead.</p>
<p>Available since: 1.1.0
Description: set beautify option for main publish channel.
Use cases: Often used in video call, live broadcasting.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Caution: In the case of using a custom video capture function, because the developer has taken over the video data capturing, the SDK is no longer responsible for the video data capturing, call this function will not take effect. When using custom video processing, the video data collected by the SDK will be handed over to the business for further processing, call this function will not take effect either.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<p>@deprecated Deprecated since 2.16.0, please use the <code>setEffectsBeautyParam</code> function instead.</p>
<ul>
<li><code>option</code> Beautify option.</li>
<li><code>channel</code> stream publish channel.</li>
</ul>



## Implementation

```dart
@Deprecated(
    'Deprecated since 2.16.0, please use the [setEffectsBeautyParam] function instead.')
Future<void> setBeautifyOption(ZegoBeautifyOption option,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setBeautifyOption(option, channel: channel);
}
```







