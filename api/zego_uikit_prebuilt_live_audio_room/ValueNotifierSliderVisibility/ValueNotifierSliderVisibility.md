


# ValueNotifierSliderVisibility constructor






const
ValueNotifierSliderVisibility({Key? key, required Widget child, required ValueNotifier&lt;bool> visibilityNotifier, Duration animationDuration = const Duration(milliseconds: 300), Offset beginOffset = Offset.zero, Offset endOffset = const Offset(0.0, 2.0)})





## Implementation

```dart
const ValueNotifierSliderVisibility({
  Key? key,
  required this.child,
  required this.visibilityNotifier,
  this.animationDuration = const Duration(milliseconds: 300),
  this.beginOffset = Offset.zero,
  this.endOffset = const Offset(0.0, 2.0),
}) : super(key: key);
```







