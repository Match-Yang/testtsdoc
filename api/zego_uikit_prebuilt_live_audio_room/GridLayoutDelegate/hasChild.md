


# hasChild method








bool hasChild
(Object childId)

_<span class="feature">inherited</span>_



<p>True if a non-null LayoutChild was provided for the specified id.</p>
<p>Call this from the <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/performLayout.md">performLayout</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/getSize.md">getSize</a> methods to
determine which children are available, if the child list might
vary.</p>



## Implementation

```dart
bool hasChild(Object childId) => _idToChild![childId] != null;
```







