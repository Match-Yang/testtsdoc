


# ZegoVideoConfig.preset constructor







ZegoVideoConfig.preset([ZegoVideoConfigPreset](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfigPreset.md) preset)


<p>Create video configuration with preset enumeration values</p>



## Implementation

```dart
ZegoVideoConfig.preset(ZegoVideoConfigPreset preset)
    : captureWidth = 720,
      captureHeight = 1280,
      encodeWidth = 720,
      encodeHeight = 1280,
      fps = 15,
      bitrate = 1200,
      codecID = ZegoVideoCodecID.Default,
      keyFrameInterval = 2 {
  codecID = ZegoVideoCodecID.Default;
  switch (preset) {
    case ZegoVideoConfigPreset.Preset180P:
      captureWidth = 180;
      captureHeight = 320;
      encodeWidth = 180;
      encodeHeight = 320;
      bitrate = 300;
      fps = 15;
      break;
    case ZegoVideoConfigPreset.Preset270P:
      captureWidth = 270;
      captureHeight = 480;
      encodeWidth = 270;
      encodeHeight = 480;
      bitrate = 400;
      fps = 15;
      break;
    case ZegoVideoConfigPreset.Preset360P:
      captureWidth = 360;
      captureHeight = 640;
      encodeWidth = 360;
      encodeHeight = 640;
      bitrate = 600;
      fps = 15;
      break;
    case ZegoVideoConfigPreset.Preset540P:
      captureWidth = 540;
      captureHeight = 960;
      encodeWidth = 540;
      encodeHeight = 960;
      bitrate = 1200;
      fps = 15;
      break;
    case ZegoVideoConfigPreset.Preset720P:
      captureWidth = 720;
      captureHeight = 1280;
      encodeWidth = 720;
      encodeHeight = 1280;
      bitrate = 1500;
      fps = 15;
      break;
    case ZegoVideoConfigPreset.Preset1080P:
      captureWidth = 1080;
      captureHeight = 1920;
      encodeWidth = 1080;
      encodeHeight = 1920;
      bitrate = 3000;
      fps = 15;
      break;
  }
}
```







