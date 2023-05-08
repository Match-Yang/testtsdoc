


# setMinVideoResolutionForTrafficControl method








Future&lt;void> setMinVideoResolutionForTrafficControl
(int width, int height, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets the minimum video resolution threshold for traffic control.</p>
<p>Available since: 2.17.0
Description: Set the control policy when the video resolution reaches the lowest threshold when flow control.
Default value: There is no control effect of the lowest threshold of video resolution.
When to call: The call takes effect after the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> is created.
Restrictions: The traffic control must be turned on <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableTrafficControl.md">enableTrafficControl</a>. And its parameter <code>property</code> must contain AdaptiveResolution, Please refer to <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoTrafficControlProperty-class.md">ZegoTrafficControlProperty</a> for details.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableTrafficControl.md">enableTrafficControl</a>.
Caution: If you need to cancel the limit of the setting value, you can set width and height to 0.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>width</code> The flow controls the width of the lowest video resolution.</li>
<li><code>height</code> The flow controls the height of the lowest video resolution.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setMinVideoResolutionForTrafficControl(int width, int height,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setMinVideoResolutionForTrafficControl(width, height,
          channel: channel);
}
```







