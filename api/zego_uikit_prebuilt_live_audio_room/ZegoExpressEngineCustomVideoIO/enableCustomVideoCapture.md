


# enableCustomVideoCapture method








Future&lt;void> enableCustomVideoCapture
(bool enable, {[ZegoCustomVideoCaptureConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoCaptureConfig-class.md)? config, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Enables or disables custom video capture (for the specified channel).</p>
<p>Available since: 1.9.0
Description: If the value of enable is true, the video collection function is enabled. If the value of enable is false, the video collection function is disabled.
Use case: The App developed by the developer uses the beauty SDK of a third-party beauty manufacturer to broadcast non-camera collected data.
Default value: When this function is not called, custom video collection is disabled by default.
When to call: After <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, call <code>startPreview</code>, <code>startPublishingStream</code>, <code>createRealTimeSequentialDataManager</code>, and call <code>logoutRoom</code> to modify the configuration.
Caution: Custom video rendering can be used in conjunction with custom video capture, but when both are enabled, the local capture frame callback for custom video rendering will no longer be triggered, and the developer should directly capture the captured video frame from the custom video capture source.
Related callbacks: When developers to open a custom collection, by calling <code>setCustomVideoCaptureHandler</code> can be set up to receive a custom collection start-stop event notification.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>enable</code> enable or disable</li>
<li><code>config</code> custom video capture config</li>
<li><code>channel</code> publish channel</li>
</ul>



## Implementation

```dart
Future<void> enableCustomVideoCapture(bool enable,
    {ZegoCustomVideoCaptureConfig? config,
    ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .enableCustomVideoCapture(enable, config: config, channel: channel);
}
```







