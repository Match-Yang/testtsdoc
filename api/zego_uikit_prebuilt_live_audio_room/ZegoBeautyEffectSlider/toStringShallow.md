


# toStringShallow method








String toStringShallow
({String joiner = ', ', DiagnosticLevel minLevel = DiagnosticLevel.debug})

_<span class="feature">inherited</span>_



<p>Returns a one-line detailed description of the object.</p>
<p>This description is often somewhat long. This includes the same
information given by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoBeautyEffectSlider/toStringDeep.md">toStringDeep</a>, but does not recurse to any children.</p>
<p><code>joiner</code> specifies the string which is place between each part obtained
from <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoBeautyEffectSlider/debugFillProperties.md">debugFillProperties</a>. Passing a string such as <code>'\n '</code> will result
in a multiline string that indents the properties of the object below its
name (as per <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoBeautyEffectSlider/toString.md">toString</a>).</p>
<p><code>minLevel</code> specifies the minimum <code>DiagnosticLevel</code> for properties included
in the output.</p>
<p>See also:</p>
<ul>
<li><a href="../../zego_uikit_prebuilt_live_audio_room/ZegoBeautyEffectSlider/toString.md">toString</a>, for a brief description of the object.</li>
<li><a href="../../zego_uikit_prebuilt_live_audio_room/ZegoBeautyEffectSlider/toStringDeep.md">toStringDeep</a>, for a description of the subtree rooted at this object.</li>
</ul>



## Implementation

```dart
String toStringShallow({
  String joiner = ', ',
  DiagnosticLevel minLevel = DiagnosticLevel.debug,
}) {
  String? shallowString;
  assert(() {
    final StringBuffer result = StringBuffer();
    result.write(toString());
    result.write(joiner);
    final DiagnosticPropertiesBuilder builder = DiagnosticPropertiesBuilder();
    debugFillProperties(builder);
    result.write(
      builder.properties.where((DiagnosticsNode n) => !n.isFiltered(minLevel))
          .join(joiner),
    );
    shallowString = result.toString();
    return true;
  }());
  return shallowString ?? toString();
}
```







