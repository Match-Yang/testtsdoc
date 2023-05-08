


# positionChild method








void positionChild
(Object childId, Offset offset)

_<span class="feature">inherited</span>_



<p>Specify the child's origin relative to this origin.</p>
<p>Call this from your <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/performLayout.md">performLayout</a> function to position each
child. If you do not call this for a child, its position will
remain unchanged. Children initially have their position set to
(0,0), i.e. the top left of the <code>RenderCustomMultiChildLayoutBox</code>.</p>



## Implementation

```dart
void positionChild(Object childId, Offset offset) {
  final RenderBox? child = _idToChild![childId];
  assert(() {
    if (child == null) {
      throw FlutterError(
        'The $this custom multichild layout delegate tried to position out a non-existent child:\n'
        'There is no child with the id "$childId".',
      );
    }
    if (offset == null) {
      throw FlutterError(
        'The $this custom multichild layout delegate provided a null position for the child with id "$childId".',
      );
    }
    return true;
  }());
  final MultiChildLayoutParentData childParentData = child!.parentData! as MultiChildLayoutParentData;
  childParentData.offset = offset;
}
```







