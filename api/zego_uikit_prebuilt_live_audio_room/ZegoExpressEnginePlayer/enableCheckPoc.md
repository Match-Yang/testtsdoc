


# enableCheckPoc method








Future&lt;void> enableCheckPoc
(bool enable)





<p>Enables or disables frame order detection.</p>
<p>Available since: 1.1.0
Description: Control whether to turn on frame order detection.
Use cases: Turning on frame order detection when pulling cdn's stream will prevent splash screens.
Default value: Turn on frame order detection by default when this interface is not called.
When to call: This function needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> creates an instance.
Restrictions: None.
Caution: Turn off frame order detection during playing stream may result in a brief splash screen.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>enable</code> Whether to turn on frame order detection, true: enable check poc, false: disable check poc.</li>
</ul>



## Implementation

```dart
Future<void> enableCheckPoc(bool enable) async {
  return await ZegoExpressImpl.instance.enableCheckPoc(enable);
}
```







