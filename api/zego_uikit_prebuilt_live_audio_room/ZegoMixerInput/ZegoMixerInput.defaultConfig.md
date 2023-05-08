


# ZegoMixerInput.defaultConfig constructor







ZegoMixerInput.defaultConfig()





## Implementation

```dart
ZegoMixerInput.defaultConfig()
    : this.streamID = "",
      this.contentType = ZegoMixerInputContentType.Video,
      this.layout = const Rect.fromLTRB(0, 0, 0, 0),
      this.soundLevelID = 0,
      this.volume = 100,
      this.isAudioFocus = false,
      this.audioDirection = -1,
      this.label = ZegoLabelInfo.text(""),
      this.renderMode = ZegoMixRenderMode.Fill,
      this.imageInfo = ZegoMixerImageInfo(""),
      this.cornerRadius = 0;
```







