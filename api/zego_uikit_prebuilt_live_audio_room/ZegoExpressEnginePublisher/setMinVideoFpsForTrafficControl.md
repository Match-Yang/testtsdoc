


# setMinVideoFpsForTrafficControl method








Future&lt;void> setMinVideoFpsForTrafficControl
(int fps, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets the minimum video frame rate threshold for traffic control.</p>
<p>Available since: 2.17.0
Description: Set the control policy when the video frame rate reaches the lowest threshold when flow control.
Default value: There is no control effect of the lowest threshold of video frame rate.
When to call: The call takes effect after the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> is created.
Restrictions: The traffic control must be turned on <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableTrafficControl.md">enableTrafficControl</a>. And its parameter <code>property</code> must contain AdaptiveFPS, Please refer to <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoTrafficControlProperty-class.md">ZegoTrafficControlProperty</a> for details.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableTrafficControl.md">enableTrafficControl</a>.
Caution: If you need to cancel the limit of the setting value, you can set it to 0.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>fps</code> The minimum video frame rate threshold for traffic control(fps).</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setMinVideoFpsForTrafficControl(int fps,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setMinVideoFpsForTrafficControl(fps, channel: channel);
}
```







