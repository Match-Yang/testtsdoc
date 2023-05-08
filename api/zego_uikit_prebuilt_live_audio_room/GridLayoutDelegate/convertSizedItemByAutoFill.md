


# convertSizedItemByAutoFill method








void convertSizedItemByAutoFill
(BoxConstraints constraints)








## Implementation

```dart
void convertSizedItemByAutoFill(BoxConstraints constraints) {
  if (autoFillItems.isEmpty) {
    return;
  }

  final itemWidth = (constraints.maxWidth -
          (columnCount - 1) * itemPadding.width -
          layoutPadding.width) /
      columnCount;
  final rowCount = (autoFillItems.length / columnCount).ceil();
  final itemHeight = (constraints.maxHeight -
          (rowCount - 1) * itemPadding.height -
          layoutPadding.height) /
      rowCount;

  sizedItems.clear();
  for (final item in autoFillItems) {
    sizedItems.add(
      GridLayoutSizedItem(
        id: item.id,
        width: itemWidth,
        height: itemHeight,
        child: item.child,
      ),
    );
  }
}
```







