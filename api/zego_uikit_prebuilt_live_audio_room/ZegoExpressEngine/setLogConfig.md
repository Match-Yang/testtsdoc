


# setLogConfig method








Future&lt;void> setLogConfig
([ZegoLogConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig-class.md) config)





<p>Set log configuration.</p>
<p>Available since: 2.3.0
Description: If you need to customize the log file size and path, please call this function to complete the configuration.
When to call: It must be set before calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> to take effect. If it is set after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, it will take effect at the next <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/destroyEngine.md">destroyEngine</a>.
Restrictions: None.
Caution: Once this interface is called, the method of setting log size and path via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setEngineConfig.md">setEngineConfig</a> will be invalid.Therefore, it is not recommended to use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setEngineConfig.md">setEngineConfig</a> to set the log size and path.</p>
<ul>
<li><code>config</code> log configuration.</li>
</ul>



## Implementation

```dart
static Future<void> setLogConfig(ZegoLogConfig config) async {
  return await ZegoExpressImpl.setLogConfig(config);
}
```







