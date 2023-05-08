


# setCloudProxyConfig method








Future&lt;void> setCloudProxyConfig
(List&lt;[ZegoProxyInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoProxyInfo-class.md)> proxyList, String token, bool enable)





<p>Set cloud proxy config.</p>
<p>Available since: 3.1.0
Description: If you need to use the cloud proxy feature, please call this function to complete the configuration.
When to call: Must be set before calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> to take effect, otherwise it will fail.
Restrictions: After <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, can not change the proxy.
Caution: None.</p>
<ul>
<li><code>proxyList</code> proxy info.</li>
<li><code>token</code> token.</li>
<li><code>enable</code> enable proxy or not.</li>
</ul>



## Implementation

```dart
static Future<void> setCloudProxyConfig(
    List<ZegoProxyInfo> proxyList, String token, bool enable) async {
  return await ZegoExpressImpl.setCloudProxyConfig(proxyList, token, enable);
}
```







