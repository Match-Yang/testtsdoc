


# setMinVideoBitrateForTrafficControl method








Future&lt;void> setMinVideoBitrateForTrafficControl
(int bitrate, [ZegoTrafficControlMinVideoBitrateMode](../../zego_uikit_prebuilt_live_audio_room/ZegoTrafficControlMinVideoBitrateMode.md) mode, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets the minimum video bitrate for traffic control for the specified publish channel.</p>
<p>Available since: 1.1.0
Description: Set the control strategy when the video bitrate reaches the lowest threshold during flow control. When the bitrate is lower than the minimum threshold, you can choose not to send video data or send it at a very low frame bitrate.
Default value: There is no control effect of the lowest threshold of video bitrate.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, Called before <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a> can take effect.
Restrictions: The traffic control must be turned on <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableTrafficControl.md">enableTrafficControl</a>.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableTrafficControl.md">enableTrafficControl</a>.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>bitrate</code> Minimum video bitrate (kbps).</li>
<li><code>mode</code> Video sending mode below the minimum bitrate.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setMinVideoBitrateForTrafficControl(
    int bitrate, ZegoTrafficControlMinVideoBitrateMode mode,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setMinVideoBitrateForTrafficControl(bitrate, mode, channel: channel);
}
```







