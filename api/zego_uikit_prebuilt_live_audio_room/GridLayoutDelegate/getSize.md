


# getSize method







- @override

Size getSize
(BoxConstraints constraints)





<p>Override this method to return the size of this object given the
incoming constraints.</p>
<p>The size cannot reflect the sizes of the children. If this layout has a
fixed width or height the returned size can reflect that; the size will be
constrained to the given constraints.</p>
<p>By default, attempts to size the box to the biggest size
possible given the constraints.</p>



## Implementation

```dart
@override
Size getSize(BoxConstraints constraints) {
  final height = _initItemsPosition(constraints);
  return Size(constraints.maxWidth, height);
}
```







