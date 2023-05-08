


# startAudioVADStableStateMonitor method








Future&lt;void> startAudioVADStableStateMonitor
([ZegoAudioVADStableStateMonitorType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVADStableStateMonitorType.md) type, {int? millisecond})





<p>Start audio VAD stable state monitoring, and the monitoring period can be set.</p>
<p>Available: since 2.17.0
Description: After monitoring is started, you can use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAudioVADStateUpdate.md">onAudioVADStateUpdate</a> callback to receive the specified type of audio VAD callback.
Use cases: For example, when you specify the type of collection and use the microphone to collect, you can check whether the host has continuous and stable voice input through this interface.
When to call: Before publish stream, you can call <code>startPreview</code> with this function and combine it with <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAudioVADStateUpdate.md">onAudioVADStateUpdate</a> callback to determine whether the audio device is working properly.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/stopAudioVADStableStateMonitor.md">stopAudioVADStableStateMonitor</a>.</p>
<ul>
<li><code>type</code> audio VAD monitor type.</li>
<li><code>millisecond</code> monitoring period</li>
</ul>



## Implementation

```dart
Future<void> startAudioVADStableStateMonitor(
    ZegoAudioVADStableStateMonitorType type,
    {int? millisecond}) async {
  return await ZegoExpressImpl.instance
      .startAudioVADStableStateMonitor(type, millisecond: millisecond);
}
```







