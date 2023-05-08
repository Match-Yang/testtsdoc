


# enableCustomVideoRender method








Future&lt;void> enableCustomVideoRender
(bool enable, [ZegoCustomVideoRenderConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoRenderConfig-class.md) config)





<p>Enables or disables custom video rendering.</p>
<p>Available since: 1.9.0
Description: When enable is <code>true</code>,video custom rendering is enabled; if the value of <code>false</code>, video custom rendering is disabled.
Use case: Use beauty features or apps that use a cross-platform UI framework (for example, Qt requires a complex hierarchical UI to achieve high-experience interaction) or game engine (e.g. Unity, Unreal Engine, Cocos)
Default value: Custom video rendering is turned off by default when this function is not called.
When to call: After <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, and before calling <code>startPreview</code>, <code>startPublishingStream</code>, <code>startPlayingStream</code>, <code>createRealTimeSequentialDataManager</code>. The configuration can only be modified after the engine is stopped, that is, after <code>logoutRoom</code> is called.
Caution: Custom video rendering can be used in conjunction with custom video capture, but when both are enabled, the local capture frame callback for custom video rendering will no longer be called back, you should directly use the captured video frame from the custom video capture source.
Related callbacks: Call <code>setCustomVideoRenderHandler</code> to set the callback to get video frame data. <code>onCapturedVideoFrameRawData</code> local preview video frame data callback, <code>onRemoteVideoFrameRawData</code> remote playing stream video frame data callback.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>enable</code> enable or disable</li>
<li><code>config</code> custom video render config</li>
</ul>



## Implementation

```dart
Future<void> enableCustomVideoRender(
    bool enable, ZegoCustomVideoRenderConfig config) async {
  return await ZegoExpressImpl.instance
      .enableCustomVideoRender(enable, config);
}
```







