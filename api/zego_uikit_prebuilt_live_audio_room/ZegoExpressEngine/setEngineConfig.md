


# setEngineConfig method








Future&lt;void> setEngineConfig
([ZegoEngineConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoEngineConfig-class.md) config)





<p>Set advanced engine configuration.</p>
<p>Available since: 1.1.0
Description: Used to enable advanced functions.
When to call: Different configurations have different call timing requirements. For details, please consult ZEGO technical support.
Restrictions: None.</p>
<ul>
<li><code>config</code> Advanced engine configuration</li>
</ul>



## Implementation

```dart
static Future<void> setEngineConfig(ZegoEngineConfig config) async {
  return await ZegoExpressImpl.setEngineConfig(config);
}
```







