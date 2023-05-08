


# debugTypicalAncestorWidgetClass property









**Annotations**

- @override
Type debugTypicalAncestorWidgetClass
  
_<span class="feature">inherited</span>_



<p>The <code>RenderObjectWidget</code> that is typically used to set up the <code>ParentData</code>
that <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutSizedItem/applyParentData.md">applyParentData</a> will write to.</p>
<p>This is only used in error messages to tell users what widget typically
wraps this ParentDataWidget.</p>



## Implementation

```dart
@override
Type get debugTypicalAncestorWidgetClass => CustomMultiChildLayout;
```








