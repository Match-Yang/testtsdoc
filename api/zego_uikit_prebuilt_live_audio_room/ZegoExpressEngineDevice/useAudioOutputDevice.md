


# useAudioOutputDevice method








Future&lt;void> useAudioOutputDevice
(int viewID, String deviceID)





<p>Switch the audio output device.</p>
<p>When to call: after using <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md">getAudioDeviceList</a> to get the list of audio output devices.
Caution: Only for Web.</p>
<ul>
<li><code>viewID</code> The viewID obtained from the createCanvasView callback function.</li>
<li><code>deviceID</code> Audio output device ID.</li>
</ul>



## Implementation

```dart
Future<void> useAudioOutputDevice(int viewID, String deviceID) async {
  return await ZegoExpressImpl.instance
      .useAudioOutputDevice(viewID, deviceID);
}
```







