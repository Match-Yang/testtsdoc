


# setActiveAudioChannel method








Future&lt;void> setActiveAudioChannel
([ZegoMediaPlayerAudioChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerAudioChannel.md) audioChannel)





<p>Set the playback channel.</p>
<p>Available since: 2.20.0
Description: Set the playback channel.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Restrictions: None.</p>
<ul>
<li><code>audioChannel</code> Playback channel, the default is ZegoMediaPlayerAudioChannelAll.</li>
</ul>



## Implementation

```dart
Future<void> setActiveAudioChannel(ZegoMediaPlayerAudioChannel audioChannel);
```







