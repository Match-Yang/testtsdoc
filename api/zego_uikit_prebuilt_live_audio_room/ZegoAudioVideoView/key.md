


# key property







Key? key
  
_<span class="feature">final</span><span class="feature">inherited</span>_



<p>Controls how one widget replaces another widget in the tree.</p>
<p>If the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoView/runtimeType.md">runtimeType</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoView/key.md">key</a> properties of the two widgets are
<a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoView/operator_equals.md">operator==</a>, respectively, then the new widget replaces the old widget by
updating the underlying element (i.e., by calling <code>Element.update</code> with the
new widget). Otherwise, the old element is removed from the tree, the new
widget is inflated into an element, and the new element is inserted into the
tree.</p>
<p>In addition, using a <code>GlobalKey</code> as the widget's <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoView/key.md">key</a> allows the element
to be moved around the tree (changing parent) without losing state. When a
new widget is found (its key and type do not match a previous widget in
the same location), but there was a widget with that same global key
elsewhere in the tree in the previous frame, then that widget's element is
moved to the new location.</p>
<p>Generally, a widget that is the only child of another widget does not need
an explicit key.</p>
<p>See also:</p>
<ul>
<li>The discussions at <code>Key</code> and <code>GlobalKey</code>.</li>
</ul>



## Implementation

```dart
final Key? key;
```







