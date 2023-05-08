


# setAllPlayStreamVolume method








Future&lt;void> setAllPlayStreamVolume
(int volume)





<p>Sets the all stream playback volume.</p>
<p>Available since: 2.3.0
Description: Set the sound size of the stream, the local user can control the playback volume of the audio stream.
When to call: after called <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/startPlayingStream.md">startPlayingStream</a>.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayVolume.md">setPlayVolume</a> Set the specified streaming volume.
Caution: You need to reset after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/stopPlayingStream.md">stopPlayingStream</a> and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/startPlayingStream.md">startPlayingStream</a>. Set the specified streaming volume and <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setAllPlayStreamVolume.md">setAllPlayStreamVolume</a> interface to override each other, and the last call takes effect.</p>
<ul>
<li><code>volume</code> Volume percentage. The value ranges from 0 to 200, and the default value is 100.</li>
</ul>



## Implementation

```dart
Future<void> setAllPlayStreamVolume(int volume) async {
  return await ZegoExpressImpl.instance.setAllPlayStreamVolume(volume);
}
```







