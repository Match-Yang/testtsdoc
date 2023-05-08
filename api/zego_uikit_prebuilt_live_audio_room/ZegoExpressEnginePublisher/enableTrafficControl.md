


# enableTrafficControl method








Future&lt;void> enableTrafficControl
(bool enable, int property)





<p>Enables or disables traffic control.</p>
<p>Available since: 1.5.0
Description: Enabling traffic control allows the SDK to adjust the audio and video streaming bitrate according to the current upstream network environment conditions, or according to the counterpart's downstream network environment conditions in a one-to-one interactive scenario, to ensure smooth results. At the same time, you can further specify the attributes of traffic control to adjust the corresponding control strategy.
Default value: Enable.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, Called before <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a> can take effect.
Restrictions: Only support RTC publish.
Caution: Act on the main publish channel ZegoPublishChannel.Main.</p>
<ul>
<li><code>enable</code> Whether to enable traffic control. The default is ture.</li>
<li><code>property</code> Adjustable property of traffic control, bitmask OR format. Should be one or the combinations of <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoTrafficControlProperty-class.md">ZegoTrafficControlProperty</a> enumeration. <code>AdaptiveFPS</code> as default.</li>
</ul>



## Implementation

```dart
Future<void> enableTrafficControl(bool enable, int property) async {
  return await ZegoExpressImpl.instance
      .enableTrafficControl(enable, property);
}
```







