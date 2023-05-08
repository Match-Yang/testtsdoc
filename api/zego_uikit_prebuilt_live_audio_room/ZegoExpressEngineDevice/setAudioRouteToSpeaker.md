


# setAudioRouteToSpeaker method








Future&lt;void> setAudioRouteToSpeaker
(bool defaultToSpeaker)





<p>Whether to use the built-in speaker to play audio.</p>
<p>Available since: 1.1.0
Description: Whether to use the speaker to play audio, when you choose not to use the built-in speaker to play the sound, the SDK will select the audio output device with the highest current priority to play the sound according to the system schedule, and common audio routes are: handsets, headphones, Bluetooth devices, and so on.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related APIs: Get the current audio route <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioRouteType.md">getAudioRouteType</a>.</p>
<ul>
<li><code>defaultToSpeaker</code> Whether to use the built-in speaker to play sound, <code>true</code>: use the built-in speaker to play sound, <code>false</code>: use the highest priority audio output device scheduled by the current system to play sound</li>
</ul>



## Implementation

```dart
Future<void> setAudioRouteToSpeaker(bool defaultToSpeaker) async {
  return await ZegoExpressImpl.instance
      .setAudioRouteToSpeaker(defaultToSpeaker);
}
```







