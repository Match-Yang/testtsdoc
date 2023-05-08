


# toMap method








Map&lt;String, dynamic> toMap
()








## Implementation

```dart
Map<String, dynamic> toMap() {
  return {
    'bitrate': this.bitrate,
    'channel': this.channel.index,
    'codecID': this.codecID.index
  };
}
```







