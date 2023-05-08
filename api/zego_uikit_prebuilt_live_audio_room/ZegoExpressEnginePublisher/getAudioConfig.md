


# getAudioConfig method








Future&lt;[ZegoAudioConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioConfig-class.md)> getAudioConfig
()





<p>Gets the current audio configurations.</p>
<p>Available since: 1.8.0
Description: You can get the current audio codec, bit rate, and audio channel through this function.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Caution: Act on the main publish channel ZegoPublishChannel.Main.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setAudioConfig.md">setAudioConfig</a>.</p>
<ul>
<li>Returns Audio config.</li>
</ul>



## Implementation

```dart
Future<ZegoAudioConfig> getAudioConfig() async {
  return await ZegoExpressImpl.instance.getAudioConfig();
}
```







