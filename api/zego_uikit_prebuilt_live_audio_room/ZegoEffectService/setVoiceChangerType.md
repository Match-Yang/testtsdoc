


# setVoiceChangerType method








void setVoiceChangerType
([ZegoVoiceChangerPreset](../../zego_uikit_prebuilt_live_audio_room/ZegoVoiceChangerPreset.md) voicePreset)





<p>Set voice changing
Description: This method can be used to change the voice with voice effects.</p>
<p>Call this method at: After joining a room</p>
<p>@param voicePreset refers to the voice type you want to changed to.</p>



## Implementation

```dart
void setVoiceChangerType(ZegoVoiceChangerPreset voicePreset) {
  ZegoLoggerService.logInfo(
    'set voice changing type: $voicePreset',
    tag: 'uikit',
    subTag: 'effect service',
  );
  ZegoExpressEngine.instance.setVoiceChangerPreset(voicePreset);
}
```







