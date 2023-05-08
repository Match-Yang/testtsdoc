


# key property









[ZegoVoiceChangerPreset](../../zego_uikit_prebuilt_live_audio_room/ZegoVoiceChangerPreset.md) key
  







## Implementation

```dart
ZegoVoiceChangerPreset get key {
  final mapValues = {
    VoiceChangerType.none: ZegoVoiceChangerPreset.None,
    VoiceChangerType.littleBoy: ZegoVoiceChangerPreset.MenToChild,
    VoiceChangerType.littleGirl: ZegoVoiceChangerPreset.WomenToChild,
    VoiceChangerType.deep: ZegoVoiceChangerPreset.MaleMagnetic,
    VoiceChangerType.crystalClear: ZegoVoiceChangerPreset.FemaleFresh,
    VoiceChangerType.robot: ZegoVoiceChangerPreset.Android,
    VoiceChangerType.ethereal: ZegoVoiceChangerPreset.Ethereal,
    VoiceChangerType.female: ZegoVoiceChangerPreset.MenToWomen,
    VoiceChangerType.male: ZegoVoiceChangerPreset.WomenToMen,
    VoiceChangerType.optimusPrime: ZegoVoiceChangerPreset.OptimusPrime,
    VoiceChangerType.cMajor: ZegoVoiceChangerPreset.MajorC,
    VoiceChangerType.aMajor: ZegoVoiceChangerPreset.MinorA,
    VoiceChangerType.harmonicMinor: ZegoVoiceChangerPreset.HarmonicMinor,
  };

  return mapValues[this]!;
}
```








