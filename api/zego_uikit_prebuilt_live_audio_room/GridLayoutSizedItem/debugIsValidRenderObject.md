


# debugIsValidRenderObject method








bool debugIsValidRenderObject
(RenderObject renderObject)

_<span class="feature">inherited</span>_



<p>Checks if this widget can apply its parent data to the provided
<code>renderObject</code>.</p>
<p>The <code>RenderObject.parentData</code> of the provided <code>renderObject</code> is
typically set up by an ancestor <code>RenderObjectWidget</code> of the type returned
by <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutSizedItem/debugTypicalAncestorWidgetClass.md">debugTypicalAncestorWidgetClass</a>.</p>
<p>This is called just before <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutSizedItem/applyParentData.md">applyParentData</a> is invoked with the same
<code>RenderObject</code> provided to that method.</p>



## Implementation

```dart
bool debugIsValidRenderObject(RenderObject renderObject) {
  assert(T != dynamic);
  assert(T != ParentData);
  return renderObject.parentData is T;
}
```







