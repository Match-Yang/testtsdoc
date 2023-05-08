


# setVideoMirrorMode method








Future&lt;void> setVideoMirrorMode
([ZegoVideoMirrorMode](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoMirrorMode.md) mirrorMode, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets the video mirroring mode (for the specified channel).</p>
<p>Available since: 1.1.0
Description: Set whether the local preview video and the published video have mirror mode enabled. For specific mirroring mode.
When to call: After <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: This setting only works if the SDK is responsible for rendering.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>mirrorMode</code> Mirror mode for previewing or publishing the stream.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setVideoMirrorMode(ZegoVideoMirrorMode mirrorMode,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setVideoMirrorMode(mirrorMode, channel: channel);
}
```







