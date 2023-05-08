


# toMap method








Map&lt;String, dynamic> toMap
()








## Implementation

```dart
Map<String, dynamic> toMap() {
  return {
    'imageURL': this.imageURL,
    'left': this.layout.left.toInt(),
    'top': this.layout.top.toInt(),
    'right': this.layout.right.toInt(),
    'bottom': this.layout.bottom.toInt(),
  };
}
```







