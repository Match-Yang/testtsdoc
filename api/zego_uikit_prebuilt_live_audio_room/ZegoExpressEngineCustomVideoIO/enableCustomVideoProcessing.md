


# enableCustomVideoProcessing method








Future&lt;void> enableCustomVideoProcessing
(bool enable, [ZegoCustomVideoProcessConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoProcessConfig-class.md) config, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Enables or disables custom video processing.</p>
<p>Available since: 2.2.0 (Android/iOS/macOS native), 2.4.0 (Windows/macOS C++).
Description: When the developer opens custom pre-processing, by calling <code>setCustomVideoProcessHandler</code> you can set the custom video pre-processing callback.
Use cases: After the developer collects the video data by himself or obtains the video data collected by the SDK, if the basic beauty and watermark functions of the SDK cannot meet the needs of the developer (for example, the beauty effect cannot meet the expectations), the ZegoEffects SDK can be used to perform the video Some special processing, such as beautifying, adding pendants, etc., this process is the pre-processing of custom video.
Default value: Off by default
When to call: Must be set before calling <code>startPreview</code>, <code>startPublishingStream</code>, <code>createRealTimeSequentialDataManager</code>. If you need to modify the configuration, please call <code>logoutRoom</code> to log out of the room first, otherwise it will not take effect.
Restrictions: None.
Related APIs: Call the <code>setCustomVideoProcessHandler</code> function to set the callback before custom video processing.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>enable</code> enable or disable. Required: Yes.</li>
<li><code>config</code> custom video processing configuration. Required: Yes.Caution: If NULL is passed, the platform default value is used.</li>
<li><code>channel</code> Publishing stream channel.Required: No.Default value: Main publish channel.</li>
</ul>



## Implementation

```dart
Future<void> enableCustomVideoProcessing(
    bool enable, ZegoCustomVideoProcessConfig config,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .enableCustomVideoProcessing(enable, config, channel: channel);
}
```







