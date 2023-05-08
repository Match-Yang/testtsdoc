


# toMap method








Map&lt;String, dynamic> toMap
()








## Implementation

```dart
Map<String, dynamic> toMap() {
  return {
    'taskID': this.taskID,
    'roomID': this.roomID,
    'audioConfig': this.audioConfig.toMap(),
    'outputList': this.outputList,
    'enableSoundLevel': this.enableSoundLevel
  };
}
```







