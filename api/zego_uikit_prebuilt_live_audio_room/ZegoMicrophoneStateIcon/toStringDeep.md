


# toStringDeep method








String toStringDeep
({String prefixLineOne = '', String? prefixOtherLines, DiagnosticLevel minLevel = DiagnosticLevel.debug})

_<span class="feature">inherited</span>_



<p>Returns a string representation of this node and its descendants.</p>
<p><code>prefixLineOne</code> will be added to the front of the first line of the
output. <code>prefixOtherLines</code> will be added to the front of each other line.
If <code>prefixOtherLines</code> is null, the <code>prefixLineOne</code> is used for every line.
By default, there is no prefix.</p>
<p><code>minLevel</code> specifies the minimum <code>DiagnosticLevel</code> for properties included
in the output.</p>
<p>The <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMicrophoneStateIcon/toStringDeep.md">toStringDeep</a> method takes other arguments, but those are intended
for internal use when recursing to the descendants, and so can be ignored.</p>
<p>See also:</p>
<ul>
<li><a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMicrophoneStateIcon/toString.md">toString</a>, for a brief description of the object but not its children.</li>
<li><a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMicrophoneStateIcon/toStringShallow.md">toStringShallow</a>, for a detailed description of the object but not its
children.</li>
</ul>



## Implementation

```dart
String toStringDeep({
  String prefixLineOne = '',
  String? prefixOtherLines,
  DiagnosticLevel minLevel = DiagnosticLevel.debug,
}) {
  return toDiagnosticsNode().toStringDeep(prefixLineOne: prefixLineOne, prefixOtherLines: prefixOtherLines, minLevel: minLevel);
}
```







