


# setAppOrientationMode method








Future&lt;void> setAppOrientationMode
([ZegoOrientationMode](../../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md) mode)





<p>Set the orientation mode of the video.</p>
<p>Available since: 2.23.0
Description: In order to simplify the complexity of processing video screen rotation for mobile developers, the SDK supports setting multiple video orientation modes, and developers can choose different modes according to the needs of the scene.
Use cases: Scenarios for live streaming or video calls using mobile devices.
Default value: Custom mode.
When to call: This function needs to be valid after calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> and before calling preview <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md">startPreview</a> or push stream <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>.
Caution:</p>
<ol>
<li>It is valid for all channels.</li>
<li>The adaptive mode takes effect in preview, streaming, and mixed streaming scenarios. It does not support external video capture, media player, cloud recording, local recording, or publishing/playing stream through CDN.
Related APIs: You can call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setAppOrientation.md">setAppOrientation</a> function to set the orientation of the App in custom mode.</li>
</ol>
<ul>
<li><code>mode</code> Orientation mode of the video.</li>
</ul>



## Implementation

```dart
Future<void> setAppOrientationMode(ZegoOrientationMode mode) async {
  return await ZegoExpressImpl.instance.setAppOrientationMode(mode);
}
```







