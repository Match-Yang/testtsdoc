


# takePublishStreamSnapshot method








Future&lt;[ZegoPublisherTakeSnapshotResult](../../zego_uikit_prebuilt_live_audio_room/ZegoPublisherTakeSnapshotResult-class.md)> takePublishStreamSnapshot
({[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Take a snapshot of the publishing stream for the specified publish channel.</p>
<p>Available since: 1.17.0
Description: Take a snapshot of the publishing stream.
When to call: Called this function after calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md">startPreview</a>.
Restrictions: None.
Caution: The resolution of the snapshot is the encoding resolution set in <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setVideoConfig.md">setVideoConfig</a>. If you need to change it to capture resolution, please call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setCapturePipelineScaleMode.md">setCapturePipelineScaleMode</a> to change the capture pipeline scale mode to <code>Post</code>.
Related callbacks: The screenshot result will be called back through <code>ZegoPublisherTakeSnapshotCallback</code>.
Related APIs: <code>takePlayStreamSnapshot</code>.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>channel</code> Publish stream channel.</li>
<li>Returns Results of take publish stream snapshot.</li>
</ul>



## Implementation

```dart
Future<ZegoPublisherTakeSnapshotResult> takePublishStreamSnapshot(
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .takePublishStreamSnapshot(channel: channel);
}
```







