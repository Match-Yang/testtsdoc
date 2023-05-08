


# setHeadphoneMonitorVolume method








Future&lt;void> setHeadphoneMonitorVolume
(int volume)





<p>Sets the headphone monitor volume.</p>
<p>Available since: 1.9.0
Description: set headphone monitor volume.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution: This setting does not actually take effect until both the headset and microphone are connected.
Related APIs: Enables or disables headphone monitoring via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableHeadphoneMonitor.md">enableHeadphoneMonitor</a>.</p>
<ul>
<li><code>volume</code> headphone monitor volume, range from 0 to 200, 60 as default.</li>
</ul>



## Implementation

```dart
Future<void> setHeadphoneMonitorVolume(int volume) async {
  return await ZegoExpressImpl.instance.setHeadphoneMonitorVolume(volume);
}
```







