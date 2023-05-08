


# stopMixerTask method








Future&lt;[ZegoMixerStopResult](../../zego_uikit_prebuilt_live_audio_room/ZegoMixerStopResult-class.md)> stopMixerTask
([ZegoMixerTask](../../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md) task)





<p>Stops a stream mixing task.</p>
<p>Available since: 1.2.1
Description: Initiate a request to end the mixing task to the ZEGO RTC server.
Use cases: It is often used when multiple video images are required to synthesize a video using mixed streaming, such as education, live broadcast of teacher and student images.
When to call: After calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer/startMixerTask.md">startMixerTask</a> to start mixing.
Restrictions: None.
Caution: If the developer starts the next mixing task without stopping the previous mixing task, the previous mixing task will not automatically stop until the input stream of the previous mixing task does not exist for 90 seconds. Before starting the next mixing task, you should stop the previous mixing task, so that when an anchor has already started the next mixing task to mix with other anchors, the audience is still pulling the output stream of the previous mixing task.
Related APIs: You can start mixing by using the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer/startMixerTask.md">startMixerTask</a> function.</p>
<ul>
<li><code>task</code> Mixing task object. Required: Yes.</li>
<li>Returns Stop stream mixing task result</li>
</ul>



## Implementation

```dart
Future<ZegoMixerStopResult> stopMixerTask(ZegoMixerTask task) async {
  return await ZegoExpressImpl.instance.stopMixerTask(task);
}
```







