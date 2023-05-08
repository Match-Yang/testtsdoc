


# createMediaPlayer method








Future&lt;[ZegoMediaPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md)?> createMediaPlayer
()





<p>Creates a media player instance.</p>
<p>Available since: 2.1.0
Description: Creates a media player instance.
Use case: It is often used to play media resource scenes, For example, play video files, push the video of media resources in combination with custom video acquisition, and the remote end can pull the stream for viewing.
When to call: It can be called after the SDK by <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> has been initialized.
Restrictions: Currently, a maximum of 4 instances can be created, after which it will return null.
Caution: The more instances of a media player, the greater the performance overhead on the device.
Related APIs: User can call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMediaPlayer/destroyMediaPlayer.md">destroyMediaPlayer</a> function to destroy a media player instance.</p>
<ul>
<li>Returns Media player instance, null will be returned when the maximum number is exceeded.</li>
</ul>



## Implementation

```dart
Future<ZegoMediaPlayer?> createMediaPlayer() async {
  return await ZegoExpressImpl.instance.createMediaPlayer();
}
```







