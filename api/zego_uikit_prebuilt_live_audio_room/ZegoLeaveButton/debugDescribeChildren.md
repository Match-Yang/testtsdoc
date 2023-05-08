


# debugDescribeChildren method







- @protected

List&lt;DiagnosticsNode> debugDescribeChildren
()

_<span class="feature">inherited</span>_



<p>Returns a list of <code>DiagnosticsNode</code> objects describing this node's
children.</p>
<p>Children that are offstage should be added with <code>style</code> set to
<code>DiagnosticsTreeStyle.offstage</code> to indicate that they are offstage.</p>
<p>The list must not contain any null entries. If there are explicit null
children to report, consider <code>DiagnosticsNode.message</code> or
<code>DiagnosticsProperty&lt;Object&gt;</code> as possible <code>DiagnosticsNode</code> objects to
provide.</p>
<p>Used by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoLeaveButton/toStringDeep.md">toStringDeep</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoLeaveButton/toDiagnosticsNode.md">toDiagnosticsNode</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoLeaveButton/toStringShallow.md">toStringShallow</a>.</p>
<p>See also:</p>
<ul>
<li><code>RenderTable.debugDescribeChildren</code>, which provides high quality custom
descriptions for its child nodes.</li>
</ul>



## Implementation

```dart
@protected
List<DiagnosticsNode> debugDescribeChildren() => const <DiagnosticsNode>[];
```







