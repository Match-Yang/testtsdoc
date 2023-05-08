


# toMap method








Map&lt;String, dynamic> toMap
()








## Implementation

```dart
Map<String, dynamic> toMap() {
  return {
    'taskID': this.taskID,
    'audioConfig': this.audioConfig.toMap(),
    'videoConfig': this.videoConfig.toMap(),
    'inputList': this.inputList,
    'outputList': this.outputList,
    'watermark': this.watermark.toMap(),
    'backgroundImageURL': this.backgroundImageURL,
    'enableSoundLevel': this.enableSoundLevel,
    'advancedConfig': this.advancedConfig,
    'minPlayStreamBufferLength': this.minPlayStreamBufferLength
  };
}
```







