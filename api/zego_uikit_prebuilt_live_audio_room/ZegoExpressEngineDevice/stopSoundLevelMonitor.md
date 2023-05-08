


# stopSoundLevelMonitor method








Future&lt;void> stopSoundLevelMonitor
()





<p>Stops sound level monitoring.</p>
<p>Available since: 1.1.0
Description: After the monitoring is stopped, the callback of the local/remote audio sound level will be stopped.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Related APIs: Soundwave monitoring can be initiated via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/startSoundLevelMonitor.md">startSoundLevelMonitor</a>.</p>



## Implementation

```dart
Future<void> stopSoundLevelMonitor() async {
  return await ZegoExpressImpl.instance.stopSoundLevelMonitor();
}
```







