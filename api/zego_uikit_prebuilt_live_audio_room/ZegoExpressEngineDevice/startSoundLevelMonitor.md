


# startSoundLevelMonitor method








Future&lt;void> startSoundLevelMonitor
({[ZegoSoundLevelConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoSoundLevelConfig-class.md)? config})





<p>Starts sound level monitoring. Support enable some advanced feature.</p>
<p>Available since: 2.10.0
Description: After starting monitoring, you can receive local audio sound level via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedSoundLevelUpdate.md">onCapturedSoundLevelUpdate</a> callback, and receive remote audio sound level via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteSoundLevelUpdate.md">onRemoteSoundLevelUpdate</a> callback. Before entering the room, you can call <code>startPreview</code> with this function and combine it with <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedSoundLevelUpdate.md">onCapturedSoundLevelUpdate</a> callback to determine whether the audio device is working properly.
Use cases: During the publishing and playing process, determine who is talking on the wheat and do a UI presentation.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution:</p>
<ol>
<li><a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedSoundLevelUpdate.md">onCapturedSoundLevelUpdate</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteSoundLevelUpdate.md">onRemoteSoundLevelUpdate</a> callback notification period is the value set by the parameter.</li>
<li>After the sound monitoring is started, even if the local audio capture is not started, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedSoundLevelUpdate.md">onCapturedSoundLevelUpdate</a> will have a callback, and the sound level is 0.</li>
</ol>
<ul>
<li><code>config</code> Configuration for starts the sound level monitor.</li>
</ul>



## Implementation

```dart
Future<void> startSoundLevelMonitor({ZegoSoundLevelConfig? config}) async {
  return await ZegoExpressImpl.instance
      .startSoundLevelMonitor(config: config);
}
```







