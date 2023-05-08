


# enableDebugAssistant method








Future&lt;void> enableDebugAssistant
(bool enable)





<p>Enable the debug assistant. Note, do not enable this feature in the online version! Use only during development phase!</p>
<p>Available since: 2.17.0
Description: After enabled, the SDK will print logs to the console, and will pop-up an alert (toast) UI message when there is a problem with calling other SDK functions.
Default value: This function is disabled by default.
When to call: This function can be called right after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Platform differences: The pop-up alert function only supports Android / iOS / macOS / Windows, and the console log function supports all platforms.
Caution: Be sure to confirm that this feature is turned off before the app is released to avoid pop-up UI alert when an error occurs in your release version's app. It is recommended to associate the <code>enable</code> parameter of this function with the DEBUG variable of the app, that is, only enable the debug assistant in the DEBUG environment.
Restrictions: None.</p>
<ul>
<li><code>enable</code> Whether to enable the debug assistant.</li>
</ul>



## Implementation

```dart
Future<void> enableDebugAssistant(bool enable) async {
  return await ZegoExpressImpl.instance.enableDebugAssistant(enable);
}
```







