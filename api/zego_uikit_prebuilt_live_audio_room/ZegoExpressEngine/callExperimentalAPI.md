


# callExperimentalAPI method








Future&lt;String> callExperimentalAPI
(String params)





<p>Call the experimental API.</p>
<p>Available since: 2.7.0
Description: ZEGO provides some technical previews or special customization functions in RTC business through this API. If you need to get the use of the function or the details, please consult ZEGO technical support.
When to call: After <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.</p>
<ul>
<li><code>params</code> Parameters in the format of a JSON string, please consult ZEGO technical support for details.</li>
<li>Returns Returns an argument in the format of a JSON string, please consult ZEGO technical support for details.</li>
</ul>



## Implementation

```dart
Future<String> callExperimentalAPI(String params) async {
  return await ZegoExpressImpl.instance.callExperimentalAPI(params);
}
```







