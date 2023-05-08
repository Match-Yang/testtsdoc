


# ZegoAutoMixerTask constructor







ZegoAutoMixerTask()


<p>Create a auto mix stream task object</p>



## Implementation

```dart
ZegoAutoMixerTask()
    : taskID = "",
      roomID = "",
      outputList = [],
      audioConfig = ZegoMixerAudioConfig.defaultConfig(),
      enableSoundLevel = false {
  taskID = "";
  roomID = "";
  outputList = [];
  audioConfig = ZegoMixerAudioConfig.defaultConfig();
  enableSoundLevel = false;
}
```







