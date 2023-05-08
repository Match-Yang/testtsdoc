


# destroyMediaPlayer method








Future&lt;void> destroyMediaPlayer
([ZegoMediaPlayer](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer)





<p>Destroys a media player instance.</p>
<p>Available since: 2.1.0
Description: Destroys a media player instance.
Related APIs: User can call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMediaPlayer/createMediaPlayer.md">createMediaPlayer</a> function to create a media player instance.</p>
<ul>
<li><code>mediaPlayer</code> The media player instance object to be destroyed.</li>
</ul>



## Implementation

```dart
Future<void> destroyMediaPlayer(ZegoMediaPlayer mediaPlayer) async {
  return await ZegoExpressImpl.instance.destroyMediaPlayer(mediaPlayer);
}
```







