


# toMap method








Map&lt;String, dynamic> toMap
()








## Implementation

```dart
Map<String, dynamic> toMap() {
  return {
    'streamID': this.streamID,
    'contentType': this.contentType.index,
    'left': this.layout.left.toInt(),
    'top': this.layout.top.toInt(),
    'right': this.layout.right.toInt(),
    'bottom': this.layout.bottom.toInt(),
    'soundLevelID': this.soundLevelID,
    'volume': this.volume,
    'isAudioFocus': this.isAudioFocus,
    'audioDirection': this.audioDirection,
    'label': this.label?.toMap(),
    'renderMode': this.renderMode?.index,
    'imageInfo': this.imageInfo?.toMap(),
    'cornerRadius': this.cornerRadius
  };
}
```







