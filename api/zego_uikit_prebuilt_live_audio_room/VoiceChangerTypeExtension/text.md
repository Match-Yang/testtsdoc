


# text property









String text
  







## Implementation

```dart
String get text {
  final mapValues = {
    VoiceChangerType.none: 'None',
    VoiceChangerType.littleBoy: 'Little boy',
    VoiceChangerType.littleGirl: 'Little girl',
    VoiceChangerType.deep: 'Deep',
    VoiceChangerType.crystalClear: 'Crystal-clear',
    VoiceChangerType.robot: 'Robot',
    VoiceChangerType.ethereal: 'Ethereal',
    VoiceChangerType.female: 'Female',
    VoiceChangerType.male: 'Male',
    VoiceChangerType.optimusPrime: 'Optimus Prime',
    VoiceChangerType.cMajor: 'C major',
    VoiceChangerType.aMajor: 'A major',
    VoiceChangerType.harmonicMinor: 'Harmonic minor',
  };

  return mapValues[this]!;
}
```








