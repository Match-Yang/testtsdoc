


# ZegoAudioConfig.preset constructor







ZegoAudioConfig.preset([ZegoAudioConfigPreset](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioConfigPreset.md) preset)


<p>Create a audio configuration with preset enumeration values</p>



## Implementation

```dart
ZegoAudioConfig.preset(ZegoAudioConfigPreset preset)
    : bitrate = 48,
      channel = ZegoAudioChannel.Mono,
      codecID = ZegoAudioCodecID.Default {
  codecID = ZegoAudioCodecID.Default;
  switch (preset) {
    case ZegoAudioConfigPreset.BasicQuality:
      bitrate = 16;
      channel = ZegoAudioChannel.Mono;
      break;
    case ZegoAudioConfigPreset.StandardQuality:
      bitrate = 48;
      channel = ZegoAudioChannel.Mono;
      break;
    case ZegoAudioConfigPreset.StandardQualityStereo:
      bitrate = 56;
      channel = ZegoAudioChannel.Stereo;
      break;
    case ZegoAudioConfigPreset.HighQuality:
      bitrate = 128;
      channel = ZegoAudioChannel.Mono;
      break;
    case ZegoAudioConfigPreset.HighQualityStereo:
      bitrate = 192;
      channel = ZegoAudioChannel.Stereo;
      break;
  }
}
```







