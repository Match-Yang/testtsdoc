


# setSEIConfig method








Future&lt;void> setSEIConfig
([ZegoSEIConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoSEIConfig-class.md) config)





<p>Set the Supplemental Enhancement Information type.</p>
<p>Available since: 1.18.0
Description: By default, the SDK wraps the data with ZEGO's self-defined SEI type, which is not specified by the SEI standard. When the developer needs to use a third-party decoder to decode the SEI, the correct SEI will not be decoded and the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setSEIConfig.md">setSEIConfig</a> interface needs to be called to change the type of the SEI sent by the SDK to UserUnregister type.
Use cases: This function needs to be executed when the developer uses a third-party decoder to decode the SEI.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before starting to push the stream <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>.
Restrictions: None.</p>
<ul>
<li><code>config</code> SEI configuration. The SEI defined by ZEGO is used by default.</li>
</ul>



## Implementation

```dart
Future<void> setSEIConfig(ZegoSEIConfig config) async {
  return await ZegoExpressImpl.instance.setSEIConfig(config);
}
```







