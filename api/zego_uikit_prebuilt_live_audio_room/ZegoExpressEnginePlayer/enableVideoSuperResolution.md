


# enableVideoSuperResolution method








Future&lt;void> enableVideoSuperResolution
(String streamID, bool enable)





<p>Enable video super resolution.</p>
<p>Available since: 3.0.0
Description: Whether to enable video super resolution when playing stream, the resolution of the played video can be doubled at the stream playing end through video super resolution. For example, the original resolution is 640x360, and the super-resolution is 1280x720.
Use cases: Live streaming scenario.
When to call: Video super resolution is only valid for playing stream video. Needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Caution:</p>
<ol>
<li>This function requires a special package, please contact ZEGO technical support;</li>
<li>This function will consume extra system resources. In order to ensure user experience, ZEGO can only enable video super resolution for one stream, and the original video resolution is not recommended to exceed 640 × 360;</li>
<li>This function has certain requirements on user equipment.
Related callbacks: Developer can use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerVideoSuperResolutionUpdate.md">onPlayerVideoSuperResolutionUpdate</a> callback to monitor the video super resolution status change.</li>
</ol>
<ul>
<li><code>streamID</code> The ID of the stream that currently needs to turn on or off overscore.</li>
<li><code>enable</code> Whether to enable super resolution, it is not enabled by default.</li>
</ul>



## Implementation

```dart
Future<void> enableVideoSuperResolution(String streamID, bool enable) async {
  return await ZegoExpressImpl.instance
      .enableVideoSuperResolution(streamID, enable);
}
```







