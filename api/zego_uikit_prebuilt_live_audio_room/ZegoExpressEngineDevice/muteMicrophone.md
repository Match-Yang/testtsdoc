


# muteMicrophone method








Future&lt;void> muteMicrophone
(bool mute)





<p>Mutes or unmutes the microphone.</p>
<p>Available since: 1.1.0
Description: This function is used to control whether to use the collected audio data. Mute (turn off the microphone) will use the muted data to replace the audio data collected by the device for streaming. At this time, the microphone device will still be occupied.
Default value: The default is <code>false</code>, which means no muting.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related APIs: Developers who want to control whether to use microphone on the UI should use this function to avoid unnecessary performance overhead by using the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableAudioCaptureDevice.md">enableAudioCaptureDevice</a>. You can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/isMicrophoneMuted.md">isMicrophoneMuted</a> to check if the microphone is muted.</p>
<ul>
<li><code>mute</code> Whether to mute (disable) the microphone, <code>true</code>: mute (disable) microphone, <code>false</code>: enable microphone.</li>
</ul>



## Implementation

```dart
Future<void> muteMicrophone(bool mute) async {
  return await ZegoExpressImpl.instance.muteMicrophone(mute);
}
```







