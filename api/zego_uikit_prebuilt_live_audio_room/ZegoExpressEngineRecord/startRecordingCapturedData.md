


# startRecordingCapturedData method








Future&lt;void> startRecordingCapturedData
([ZegoDataRecordConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordConfig-class.md) config, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Starts to record and directly save the data to a file.</p>
<p>Available since: 1.10.0
Description: Starts to record locally captured audio or video and directly save the data to a file, The recorded data will be the same as the data publishing through the specified channel.
Restrictions: None.
Caution: Developers should not <code>stopPreview</code> or <code>stopPublishingStream</code> during recording, otherwise the SDK will end the current recording task. The data of the media player needs to be mixed into the publishing stream to be recorded.
Related callbacks: Developers will receive the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedDataRecordStateUpdate.md">onCapturedDataRecordStateUpdate</a> and the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedDataRecordProgressUpdate.md">onCapturedDataRecordProgressUpdate</a> callback after start recording.</p>
<ul>
<li><code>config</code> Record config.</li>
<li><code>channel</code> Publishing stream channel.</li>
</ul>



## Implementation

```dart
Future<void> startRecordingCapturedData(ZegoDataRecordConfig config,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .startRecordingCapturedData(config, channel: channel);
}
```







