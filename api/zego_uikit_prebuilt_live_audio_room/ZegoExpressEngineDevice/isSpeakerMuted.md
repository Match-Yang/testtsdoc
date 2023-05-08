


# isSpeakerMuted method








Future&lt;bool> isSpeakerMuted
()





<p>Checks whether the audio output speaker is muted.</p>
<p>Available since: 1.1.0
Description: Used to determine whether the audio output is muted.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/muteSpeaker.md">muteSpeaker</a>.</p>
<ul>
<li>Returns Whether the speaker is muted; <code>true</code>: the speaker is muted; <code>false</code>: the speaker is enable (not muted).</li>
</ul>



## Implementation

```dart
Future<bool> isSpeakerMuted() async {
  return await ZegoExpressImpl.instance.isSpeakerMuted();
}
```







