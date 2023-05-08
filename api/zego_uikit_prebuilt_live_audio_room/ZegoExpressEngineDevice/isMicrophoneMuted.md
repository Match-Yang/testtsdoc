


# isMicrophoneMuted method








Future&lt;bool> isMicrophoneMuted
()





<p>Checks whether the microphone is muted.</p>
<p>Available since: 1.1.0
Description: Used to determine whether the microphone is set to mute.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/muteMicrophone.md">muteMicrophone</a>.</p>
<ul>
<li>Returns Whether the microphone is muted; true: the microphone is muted; <code>false</code>: the microphone is enable (not muted).</li>
</ul>



## Implementation

```dart
Future<bool> isMicrophoneMuted() async {
  return await ZegoExpressImpl.instance.isMicrophoneMuted();
}
```







