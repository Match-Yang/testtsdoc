


# setMixSystemPlayoutVolume method








Future&lt;void> setMixSystemPlayoutVolume
(int volume)





<p>set system audio capture volume.</p>
<p>Available since: 2.4.0
Description:  set system audio capture volume.
Use cases: User needs to adjust the volume which system playout mix to stream publishing.
When to call /Trigger: Called this function after calling <code>startPublishingStream</code> or <code>startPreview</code>.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableMixSystemPlayout.md">enableMixSystemPlayout</a> enable or disable mix system playout.
Platform differences: Only supports Windows and macOS.</p>
<ul>
<li><code>volume</code> the volume. Valid range <code>0, 200</code>, default is 100.</li>
</ul>



## Implementation

```dart
Future<void> setMixSystemPlayoutVolume(int volume) async {
  return await ZegoExpressImpl.instance.setMixSystemPlayoutVolume(volume);
}
```







