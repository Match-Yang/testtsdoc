


# enableHeadphoneMonitor method








Future&lt;void> enableHeadphoneMonitor
(bool enable)





<p>Enables or disables headphone monitoring.</p>
<p>Available since: 1.9.0
Description: Enable/Disable headphone monitor, and users hear their own voices as they use the microphone to capture sounds.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Default value: Disable.
Caution:</p>
<ol>
<li>This setting does not actually take effect until both the headset and microphone are connected.</li>
<li>The default is to return after acquisition and before pre-processing. If you need to return after pre-processing, please contact ZEGO technical support.</li>
</ol>
<ul>
<li><code>enable</code> Whether to use headphone monitor, true: enable, false: disable</li>
</ul>



## Implementation

```dart
Future<void> enableHeadphoneMonitor(bool enable) async {
  return await ZegoExpressImpl.instance.enableHeadphoneMonitor(enable);
}
```







