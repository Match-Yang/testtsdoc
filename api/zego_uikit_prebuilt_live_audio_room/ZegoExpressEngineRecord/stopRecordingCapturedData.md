


# stopRecordingCapturedData method








Future&lt;void> stopRecordingCapturedData
({[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Stops recording locally captured audio or video.</p>
<p>Available since: 1.10.0
Description: Stops recording locally captured audio or video.
When to call: After <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRecord/startRecordingCapturedData.md">startRecordingCapturedData</a>.
Restrictions: None.</p>
<ul>
<li><code>channel</code> Publishing stream channel.</li>
</ul>



## Implementation

```dart
Future<void> stopRecordingCapturedData({ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .stopRecordingCapturedData(channel: channel);
}
```







