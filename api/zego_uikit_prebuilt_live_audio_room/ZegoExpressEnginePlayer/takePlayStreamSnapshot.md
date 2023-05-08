


# takePlayStreamSnapshot method








Future&lt;[ZegoPlayerTakeSnapshotResult](../../zego_uikit_prebuilt_live_audio_room/ZegoPlayerTakeSnapshotResult-class.md)> takePlayStreamSnapshot
(String streamID)





<p>Take a snapshot of the playing stream.</p>
<p>Available since: 1.17.0
Description: Take a screenshot of the specified stream ID.
When to call: after called <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/startPlayingStream.md">startPlayingStream</a>.
Restrictions: None.
Related callbacks: <code>onPlayerTakeSnapshotResult</code> Screenshot data callback.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>streamID</code> Stream ID to be snapshot.</li>
<li>Returns Results of take play stream snapshot.</li>
</ul>



## Implementation

```dart
Future<ZegoPlayerTakeSnapshotResult> takePlayStreamSnapshot(
    String streamID) async {
  return await ZegoExpressImpl.instance.takePlayStreamSnapshot(streamID);
}
```







