


# startMixerTask method








Future&lt;[ZegoMixerStartResult](../../zego_uikit_prebuilt_live_audio_room/ZegoMixerStartResult-class.md)> startMixerTask
([ZegoMixerTask](../../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md) task)





<p>Starts a stream mixing task.</p>
<p>Available since: 1.2.1
Description: Initiate a mixing stream request to the ZEGO RTC server, the server will look for the stream currently being pushed, and mix the layers according to the parameters of the mixing stream task requested by the SDK. When you need to update a mixing task, that is, when the input stream increases or decreases, you need to update the input stream list. At this time, you can update the field of the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md">ZegoMixerTask</a> object inputList and call this function again to pass in the same <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md">ZegoMixerTask</a> object to update the mixing task.
Use cases: It is often used when multiple video images are required to synthesize a video using mixed streaming, such as education, live broadcast of teacher and student images.
When to call: After calling <code>loginRoom</code> to log in to the room.
Restrictions: None.
Caution: Due to the performance considerations of the client device, the SDK muxing is to start the mixing task on the ZEGO RTC server for mixing. If an exception occurs when the mixing task is requested to start, for example, the most common mixing input stream does not exist, the error code will be given from the callback callback. If a certain input stream does not exist in the middle, the muxing task will automatically retry to pull this input stream for 90 seconds, and will not retry after 90 seconds. If all input streams no longer exist, the server will automatically stop the mixing task after 90 seconds.
Related callbacks: <code>OnMixerRelayCDNStateUpdate</code> can be used to obtain the CDN status update notification of the mixed stream repost, and the sound update notification of each single stream in the mixed stream can be obtained through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMixerSoundLevelUpdate.md">onMixerSoundLevelUpdate</a>.
Related APIs: the mixing task can be stopped by the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer/stopMixerTask.md">stopMixerTask</a> function.</p>
<ul>
<li><code>task</code> Mixing task object. Required: Yes.</li>
<li>Returns Start stream mixing task result callback notification</li>
</ul>



## Implementation

```dart
Future<ZegoMixerStartResult> startMixerTask(ZegoMixerTask task) async {
  return await ZegoExpressImpl.instance.startMixerTask(task);
}
```







