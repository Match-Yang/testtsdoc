


# startAutoMixerTask method








Future&lt;[ZegoMixerStartResult](../../zego_uikit_prebuilt_live_audio_room/ZegoMixerStartResult-class.md)> startAutoMixerTask
([ZegoAutoMixerTask](../../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask-class.md) task)





<p>Starts an auto stream mixing task.</p>
<p>Available since: 2.10.0
Description: Local users can use this function to start an auto stream mixing task, all streams in a room wil be mixed. Currently, only audio streams can be mixed. When auto stream mixing is enabled, the audio of all streams in the room is automatically mixed, and any further pushed streams in the room are automatically mixed into the final output stream.
Use cases: Often used in voice chat room scenarios.
When to call: After the engine is created, user can call this function to enable auto stream mixing in the target room if the target room has already been created
Restrictions: Please refer to <a href="https://docs.zegocloud.com/article/7611">https://docs.zegocloud.com/article/7611</a> or contact ZEGO technical support.
Caution: Before starting the next auto stream mixing task in the same room, call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer/stopAutoMixerTask.md">stopAutoMixerTask</a> function to end the last auto stream mixing task. Otherwise, when one anchor has started the next auto stream mixing task and other anchors have started the next auto stream mixing task, the audience still pulls the output stream of the first auto stream mixing task. If the user does not end the current auto stream mixing task, the task will automatically end after the room does not exist or the input streams do not exist for 90 seconds.
Related callbacks: Users can obtain the execution result of the function through <code>ZegoMixerStartCallback</code> callback.Users can get automatic mixed flow information through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAutoMixerSoundLevelUpdate.md">onAutoMixerSoundLevelUpdate</a> callback.
Related APIs: Users can call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer/stopAutoMixerTask.md">stopAutoMixerTask</a> function to stop an auto stream mixing task.</p>
<ul>
<li><code>task</code> Auto mix stream task object</li>
<li>Returns Start auto mix stream task result callback notification</li>
</ul>



## Implementation

```dart
Future<ZegoMixerStartResult> startAutoMixerTask(
    ZegoAutoMixerTask task) async {
  return await ZegoExpressImpl.instance.startAutoMixerTask(task);
}
```







