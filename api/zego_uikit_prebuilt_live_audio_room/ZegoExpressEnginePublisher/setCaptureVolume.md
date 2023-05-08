


# setCaptureVolume method








Future&lt;void> setCaptureVolume
(int volume)





<p>Sets the audio recording volume for stream publishing.</p>
<p>Available since: 1.13.0
Description: This function is used to perform gain processing based on the device's collected volume. The local user can control the sound level of the audio stream sent to the remote end.
Default value: Default is 100.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: The capture volume can be dynamically set during publishing.
Related APIs: Set the playing stream volume <code>setPlayVolume</code>.</p>
<ul>
<li><code>volume</code> The volume gain percentage, the range is 0 ~ 200, and the default value is 100, which means 100% of the original collection volume of the device.</li>
</ul>



## Implementation

```dart
Future<void> setCaptureVolume(int volume) async {
  return await ZegoExpressImpl.instance.setCaptureVolume(volume);
}
```







