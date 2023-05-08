


# toStringShort method







- @override

String toStringShort
()

_<span class="feature">inherited</span>_



<p>A short, textual description of this widget.</p>



## Implementation

```dart
@override
String toStringShort() {
  final String type = objectRuntimeType(this, 'Widget');
  return key == null ? type : '$type-$key';
}
```







