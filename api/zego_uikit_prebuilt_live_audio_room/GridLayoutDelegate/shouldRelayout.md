


# shouldRelayout method







- @override

bool shouldRelayout
(covariant MultiChildLayoutDelegate oldDelegate)





<p>Override this method to return true when the children need to be
laid out.</p>
<p>This should compare the fields of the current delegate and the given
<code>oldDelegate</code> and return true if the fields are such that the layout would
be different.</p>



## Implementation

```dart
@override
bool shouldRelayout(covariant MultiChildLayoutDelegate oldDelegate) {
  return true;
}
```







