


# applyParentData method







- @override

void applyParentData
(RenderObject renderObject)

_<span class="feature">inherited</span>_



<p>Write the data from this widget into the given render object's parent data.</p>
<p>The framework calls this function whenever it detects that the
<code>RenderObject</code> associated with the <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutSizedItem/child.md">child</a> has outdated
<code>RenderObject.parentData</code>. For example, if the render object was recently
inserted into the render tree, the render object's parent data might not
match the data in this widget.</p>
<p>Subclasses are expected to override this function to copy data from their
fields into the <code>RenderObject.parentData</code> field of the given render
object. The render object's parent is guaranteed to have been created by a
widget of type <code>T</code>, which usually means that this function can assume that
the render object's parent data object inherits from a particular class.</p>
<p>If this function modifies data that can change the parent's layout or
painting, this function is responsible for calling
<code>RenderObject.markNeedsLayout</code> or <code>RenderObject.markNeedsPaint</code> on the
parent, as appropriate.</p>



## Implementation

```dart
@override
void applyParentData(RenderObject renderObject) {
  assert(renderObject.parentData is MultiChildLayoutParentData);
  final MultiChildLayoutParentData parentData = renderObject.parentData! as MultiChildLayoutParentData;
  if (parentData.id != id) {
    parentData.id = id;
    final AbstractNode? targetParent = renderObject.parent;
    if (targetParent is RenderObject) {
      targetParent.markNeedsLayout();
    }
  }
}
```







