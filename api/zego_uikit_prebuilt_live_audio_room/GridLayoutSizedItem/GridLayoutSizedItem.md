


# GridLayoutSizedItem constructor







GridLayoutSizedItem({Key? key, required Object id, required Widget child, required double width, required double height})





## Implementation

```dart
GridLayoutSizedItem({
  Key? key,
  required Object id,
  required Widget child,
  required this.width,
  required this.height,
})  : assert(width > 0),
      assert(height > 0),
      super(key: key, child: child, id: id);
```







