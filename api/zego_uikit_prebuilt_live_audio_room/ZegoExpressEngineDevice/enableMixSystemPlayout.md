


# enableMixSystemPlayout method








Future&lt;void> enableMixSystemPlayout
(bool enable)





<p>Enable or disable system audio capture.</p>
<p>Available since: 1.9.0
Description: Enable sound card capture to mix sounds played by the system into the publishing stream, such as sounds played by the browser, sounds played by the third-party player, etc.
Default value: Default is disable.
When to call: Called this function after calling <code>startPublishingStream</code> or <code>startPreview</code>.
Restrictions: None.
Caution: The system sound card sound does not include streaming sound, media player sound and sound effect player sound.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setMixSystemPlayoutVolume.md">setMixSystemPlayoutVolume</a> function can set system audio capture volume.
Platform differences: Only supports Windows and macOS.</p>
<ul>
<li><code>enable</code> Whether to mix system playout.</li>
</ul>



## Implementation

```dart
Future<void> enableMixSystemPlayout(bool enable) async {
  return await ZegoExpressImpl.instance.enableMixSystemPlayout(enable);
}
```







