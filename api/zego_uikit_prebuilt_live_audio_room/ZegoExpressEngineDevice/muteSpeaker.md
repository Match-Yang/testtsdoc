


# muteSpeaker method








Future&lt;void> muteSpeaker
(bool mute)





<p>Mutes or unmutes the audio output speaker.</p>
<p>Available since: 1.1.0
Description: After mute speaker, all the SDK sounds will not play, including playing stream, mediaplayer, etc. But the SDK will still occupy the output device.
Default value: The default is <code>false</code>, which means no muting.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.</p>
<ul>
<li><code>mute</code> Whether to mute (disable) speaker audio output, <code>true</code>: mute (disable) speaker audio output, <code>false</code>: enable speaker audio output.</li>
</ul>



## Implementation

```dart
Future<void> muteSpeaker(bool mute) async {
  return await ZegoExpressImpl.instance.muteSpeaker(mute);
}
```







