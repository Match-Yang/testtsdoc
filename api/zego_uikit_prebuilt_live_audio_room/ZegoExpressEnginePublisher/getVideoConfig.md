


# getVideoConfig method








Future&lt;[ZegoVideoConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig-class.md)> getVideoConfig
({[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Gets the current video configurations (for the specified channel).</p>
<p>This function can be used to get the specified publish channel's current video frame rate, bit rate, video capture resolution, and video encoding output resolution.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>channel</code> Publish stream channel</li>
<li>Returns Video configuration object</li>
</ul>



## Implementation

```dart
Future<ZegoVideoConfig> getVideoConfig({ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance.getVideoConfig(channel: channel);
}
```







