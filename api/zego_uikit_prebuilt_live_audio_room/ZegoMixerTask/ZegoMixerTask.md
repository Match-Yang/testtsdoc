


# ZegoMixerTask constructor







ZegoMixerTask(String taskID)


<p>Create a mix stream task object with TaskID</p>



## Implementation

```dart
ZegoMixerTask(this.taskID)
    : inputList = [],
      outputList = [],
      audioConfig = ZegoMixerAudioConfig.defaultConfig(),
      videoConfig = ZegoMixerVideoConfig.defaultConfig(),
      watermark = ZegoWatermark('', const Rect.fromLTRB(0, 0, 0, 0)),
      backgroundImageURL = "",
      enableSoundLevel = false,
      advancedConfig = {},
      minPlayStreamBufferLength = -1;
```







