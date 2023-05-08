


# setReverbType method








void setReverbType
([ZegoReverbPreset](../../zego_uikit_prebuilt_live_audio_room/ZegoReverbPreset.md) reverbPreset)





<p>Set reverb
Description: This method can be used to use the reverb effect in the room.</p>
<p>Call this method at: After joining a room</p>
<p>@param reverbPreset refers to the reverb type you want to select.</p>



## Implementation

```dart
void setReverbType(ZegoReverbPreset reverbPreset) {
  ZegoLoggerService.logInfo(
    'set reverb type: $reverbPreset',
    tag: 'uikit',
    subTag: 'effect service',
  );
  ZegoExpressEngine.instance.setReverbPreset(reverbPreset);
}
```







