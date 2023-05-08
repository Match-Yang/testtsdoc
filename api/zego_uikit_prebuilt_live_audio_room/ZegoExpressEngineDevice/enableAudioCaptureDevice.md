


# enableAudioCaptureDevice method








Future&lt;void> enableAudioCaptureDevice
(bool enable)





<p>Enables or disables the audio capture device.</p>
<p>Available since: 1.1.0
Description: This function is used to control whether to use the audio collection device. When the audio collection device is turned off, the SDK will no longer occupy the audio device. Of course, if the stream is being published at this time, there is no audio data.
Use cases: When the user never needs to use the audio, you can call this function to close the audio collection.
Default value: The default is <code>true</code>.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related APIs: Turning off or turning on the microphone on the hardware is a time-consuming operation, and there is a certain performance overhead when the user performs frequent operations. <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/muteMicrophone.md">muteMicrophone</a> is generally recommended.</p>
<ul>
<li><code>enable</code> Whether to enable the audio capture device, <code>true</code>: enable audio capture device, <code>false</code>: disable audio capture device.</li>
</ul>



## Implementation

```dart
Future<void> enableAudioCaptureDevice(bool enable) async {
  return await ZegoExpressImpl.instance.enableAudioCaptureDevice(enable);
}
```







