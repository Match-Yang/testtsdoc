


# toMap method








Map&lt;String, dynamic> toMap
()








## Implementation

```dart
Map<String, dynamic> toMap() {
  return {
    'text': this.text,
    'left': this.left,
    'top': this.top,
    'font': this.font.toMap()
  };
}
```







