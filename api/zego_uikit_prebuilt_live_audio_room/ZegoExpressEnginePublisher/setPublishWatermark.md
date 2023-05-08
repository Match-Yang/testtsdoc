


# setPublishWatermark method








Future&lt;void> setPublishWatermark
({[ZegoWatermark](../../zego_uikit_prebuilt_live_audio_room/ZegoWatermark-class.md)? watermark, bool? isPreviewVisible, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets up the stream watermark before stream publishing (for the specified channel).</p>
<p>Available since: 1.1.0
Description: Set watermark for publish stream screen.
Use cases: It is often used to identify the source of the publish.
When to call: After creating the engine through <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> function.
Caution: The layout of the watermark cannot exceed the video encoding resolution of the stream. It can be set at any time before or during the publishing stream.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>watermark</code> The upper left corner of the watermark layout is the origin of the coordinate system, and the area cannot exceed the size set by the encoding resolution. If it is null, the watermark is cancelled. It supports Flutter assets resources, just set the 'imageURL' parameter of the watermark object to the prefix of 'flutter-asset://' and append the relative path of the resource file declared in 'pubspec.yaml'. For example, assuming that 'assets: - images/logo.png' is declared in 'pubspec.yaml', then set 'imageURL' parameter to 'flutter-asset://images/logo.png'.</li>
<li><code>isPreviewVisible</code> the watermark is visible on local preview</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setPublishWatermark(
    {ZegoWatermark? watermark,
    bool? isPreviewVisible,
    ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance.setPublishWatermark(
      watermark: watermark,
      isPreviewVisible: isPreviewVisible,
      channel: channel);
}
```







