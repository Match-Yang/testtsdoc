


# toMap method








Map&lt;String, dynamic> toMap
()








## Implementation

```dart
Map<String, dynamic> toMap() {
  return {
    'type': this.type.index,
    'size': this.size,
    'color': this.color,
    'transparency': this.transparency,
    'border': this.border,
    'borderColor': this.borderColor
  };
}
```







