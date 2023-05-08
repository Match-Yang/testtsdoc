


# layoutChild method








Size layoutChild
(Object childId, BoxConstraints constraints)

_<span class="feature">inherited</span>_



<p>Ask the child to update its layout within the limits specified by
the constraints parameter. The child's size is returned.</p>
<p>Call this from your <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/performLayout.md">performLayout</a> function to lay out each
child. Every child must be laid out using this function exactly
once each time the <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/performLayout.md">performLayout</a> function is called.</p>



## Implementation

```dart
Size layoutChild(Object childId, BoxConstraints constraints) {
  final RenderBox? child = _idToChild![childId];
  assert(() {
    if (child == null) {
      throw FlutterError(
        'The $this custom multichild layout delegate tried to lay out a non-existent child.\n'
        'There is no child with the id "$childId".',
      );
    }
    if (!_debugChildrenNeedingLayout!.remove(child)) {
      throw FlutterError(
        'The $this custom multichild layout delegate tried to lay out the child with id "$childId" more than once.\n'
        'Each child must be laid out exactly once.',
      );
    }
    try {
      assert(constraints.debugAssertIsValid(isAppliedConstraint: true));
    } on AssertionError catch (exception) {
      throw FlutterError.fromParts(<DiagnosticsNode>[
        ErrorSummary('The $this custom multichild layout delegate provided invalid box constraints for the child with id "$childId".'),
        DiagnosticsProperty<AssertionError>('Exception', exception, showName: false),
        ErrorDescription(
          'The minimum width and height must be greater than or equal to zero.\n'
          'The maximum width must be greater than or equal to the minimum width.\n'
          'The maximum height must be greater than or equal to the minimum height.',
        ),
      ]);
    }
    return true;
  }());
  child!.layout(constraints, parentUsesSize: true);
  return child.size;
}
```







