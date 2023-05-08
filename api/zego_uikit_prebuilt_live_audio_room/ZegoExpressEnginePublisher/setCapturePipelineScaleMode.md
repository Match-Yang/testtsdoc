


# setCapturePipelineScaleMode method








Future&lt;void> setCapturePipelineScaleMode
([ZegoCapturePipelineScaleMode](../../zego_uikit_prebuilt_live_audio_room/ZegoCapturePipelineScaleMode.md) mode)





<p>Sets the timing of video scaling in the video capture workflow. You can choose to do video scaling right after video capture (the default value) or before encoding.</p>
<p>Available since: 1.1.0
When to call: This function needs to be set before call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md">startPreview</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>.
Caution: The main effect is Whether the local preview is affected when the acquisition resolution is different from the encoding resolution.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>mode</code> The capture scale timing mode.</li>
</ul>



## Implementation

```dart
Future<void> setCapturePipelineScaleMode(
    ZegoCapturePipelineScaleMode mode) async {
  return await ZegoExpressImpl.instance.setCapturePipelineScaleMode(mode);
}
```







