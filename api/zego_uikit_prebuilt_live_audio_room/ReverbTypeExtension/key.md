


# key property









[ZegoReverbPreset](../../zego_uikit_prebuilt_live_audio_room/ZegoReverbPreset.md) key
  







## Implementation

```dart
ZegoReverbPreset get key {
  final mapValues = {
    ReverbType.ktv: ZegoReverbPreset.KTV,
    ReverbType.hall: ZegoReverbPreset.ConcertHall,
    ReverbType.concert: ZegoReverbPreset.VocalConcert,
    ReverbType.rock: ZegoReverbPreset.Rock,
    ReverbType.none: ZegoReverbPreset.None,
    ReverbType.smallRoom: ZegoReverbPreset.SoftRoom,
    ReverbType.largeRoom: ZegoReverbPreset.LargeRoom,
    ReverbType.valley: ZegoReverbPreset.Valley,
    ReverbType.recordingStudio: ZegoReverbPreset.RecordingStudio,
    ReverbType.basement: ZegoReverbPreset.Basement,
    ReverbType.popular: ZegoReverbPreset.Popular,
    ReverbType.gramophone: ZegoReverbPreset.GramoPhone,
  };

  return mapValues[this]!;
}
```








