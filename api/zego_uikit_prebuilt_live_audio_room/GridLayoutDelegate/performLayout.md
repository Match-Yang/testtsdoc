


# performLayout method







- @override

void performLayout
(Size size)





<p>Override this method to lay out and position all children given this
widget's size.</p>
<p>This method must call <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/layoutChild.md">layoutChild</a> for each child. It should also specify
the final position of each child with <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/positionChild.md">positionChild</a>.</p>



## Implementation

```dart
@override
void performLayout(Size size) {
  for (var itemIndex = 0; itemIndex < sizedItems.length;) {
    final item = sizedItems.elementAt(itemIndex);
    final itemPos = itemsPosition.elementAt(itemIndex);
    layoutChild(item.id, BoxConstraints.tight(Size(item.width, item.height)));
    positionChild(item.id, itemPos);

    itemIndex++;
  }
}
```







