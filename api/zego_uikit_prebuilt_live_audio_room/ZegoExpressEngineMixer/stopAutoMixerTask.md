


# stopAutoMixerTask method








Future&lt;[ZegoMixerStopResult](../../zego_uikit_prebuilt_live_audio_room/ZegoMixerStopResult-class.md)> stopAutoMixerTask
([ZegoAutoMixerTask](../../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask-class.md) task)





<p>Stops an auto stream mixing task.</p>
<p>Available since: 2.10.0
Description: Local users can use this function to stop an auto stream mixing task.
Use cases: Often used in voice chat room scenarios.
When to call: Call this function after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer/startAutoMixerTask.md">startAutoMixerTask</a> function is called to start an auto stream mixing task.
Caution: Before calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer/startAutoMixerTask.md">startAutoMixerTask</a> function to start the next auto stream mixing task in the same room, call this function to end the last auto stream mixing task. Otherwise, when one anchor has started the next auto stream mixing task and other anchors have started the next auto stream mixing task, the audience still pulls the output stream of the first auto stream mixing task. If the user does not end the current auto stream mixing task, the task will automatically end after the room does not exist or the input streams do not exist for 90 seconds.
Related callbacks: Users can obtain the execution result of the function through <code>ZegoMixerStopCallback</code> callback.
Related APIs: Users can call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer/startAutoMixerTask.md">startAutoMixerTask</a> function to start an auto stream mixing task.</p>
<ul>
<li><code>task</code> Auto mix stream task object</li>
<li>Returns Stop auto mix stream task result callback notification</li>
</ul>



## Implementation

```dart
Future<ZegoMixerStopResult> stopAutoMixerTask(ZegoAutoMixerTask task) async {
  return await ZegoExpressImpl.instance.stopAutoMixerTask(task);
}
```







