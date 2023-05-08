


# enableMixEnginePlayout method








Future&lt;void> enableMixEnginePlayout
(bool enable)





<p>Enable or disable mix SDK playout to stream publishing.</p>
<p>Available since: 1.0.0
Description: Enable mix SDK playout sounds into the stream publishing.
Use cases: Users need to mix the sound of SDK playout into stream publishing. For example, when the class scene, the teacher and student Co-hosting, and the teacher can mix the play streaming sound into the publish streaming.
Default value: Default is disable.
When to call /Trigger: Called this function after calling <code>startPublishingStream</code> or <code>startPreview</code>.
Restrictions: None.
Platform differences: Only supports Windows and macOS.</p>
<ul>
<li><code>enable</code> Whether to mix engine playout</li>
</ul>



## Implementation

```dart
Future<void> enableMixEnginePlayout(bool enable) async {
  return await ZegoExpressImpl.instance.enableMixEnginePlayout(enable);
}
```







