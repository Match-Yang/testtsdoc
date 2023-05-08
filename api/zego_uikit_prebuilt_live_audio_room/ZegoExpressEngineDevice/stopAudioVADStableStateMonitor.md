


# stopAudioVADStableStateMonitor method








Future&lt;void> stopAudioVADStableStateMonitor
([ZegoAudioVADStableStateMonitorType](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVADStableStateMonitorType.md) type)





<p>Stop audio VAD stable state monitoring.</p>
<p>Available: since 2.14.0
Description: After calling this interface, the specified type of <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAudioVADStateUpdate.md">onAudioVADStateUpdate</a> callback can no longer be received.
When to call: None.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/startAudioVADStableStateMonitor.md">startAudioVADStableStateMonitor</a>.</p>
<ul>
<li><code>type</code> audio VAD monitor type.</li>
</ul>



## Implementation

```dart
Future<void> stopAudioVADStableStateMonitor(
    ZegoAudioVADStableStateMonitorType type) async {
  return await ZegoExpressImpl.instance.stopAudioVADStableStateMonitor(type);
}
```







