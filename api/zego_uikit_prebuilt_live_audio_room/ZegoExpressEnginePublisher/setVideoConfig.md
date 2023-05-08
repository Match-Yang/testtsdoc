


# setVideoConfig method








Future&lt;void> setVideoConfig
([ZegoVideoConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig-class.md) config, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets up the video configurations (for the specified channel).</p>
<p>Available since: 1.1.0
Description: Set the video frame rate, bit rate, video capture resolution, and video encoding output resolution.
Default value: The default video capture resolution is 360p, the video encoding output resolution is 360p, the bit rate is 600 kbps, and the frame rate is 15 fps.
When to call: After <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: It is necessary to set the relevant video configuration before <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md">startPreview</a>, and only support the modification of the encoding resolution and the bit rate after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md">startPreview</a>.
Caution: Developers should note that the wide and high resolution of the mobile end is opposite to the wide and high resolution of the PC. For example, in the case of 360p, the resolution of the mobile end is 360x640, and the resolution of the PC end is 640x360.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>config</code> Video configuration, the SDK provides a common setting combination of resolution, frame rate and bit rate, they also can be customized.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setVideoConfig(ZegoVideoConfig config,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setVideoConfig(config, channel: channel);
}
```







