


# setStreamVocalRange method








Future&lt;void> setStreamVocalRange
(String streamID, double vocalRange)





<p>Set the sound range for the stream.</p>
<p>Available since: 2.23.0
Description: Set range voice volume.
Use case: When a user calls <code>startPlayingStream</code> and pulls another stream, the stream has a range speech effect by setting the range of sounds for that stream and calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/updateStreamPosition.md">updateStreamPosition</a>. After the call will be the sound source of the sound range of the distance attenuation effect.
When to call: After initializing the range audio <code>createRangeAudio</code> and after <code>startPlayingStream</code>.
Caution:  When calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/enableMicrophone.md">enableMicrophone</a> to enable range speech, the resource of the stream will be switched to RTC, regardless of whether the resource specified when <code>startPlayingStream</code> was originally called to pull the stream is RTC. If you really need to specify the resource of the stream as CDN, please configure it to pull a custom CDN stream and specify the CDN address information.</p>
<ul>
<li><code>streamID</code> play stream id</li>
<li><code>vocalRange</code> Flow sound range.</li>
</ul>



## Implementation

```dart
Future<void> setStreamVocalRange(String streamID, double vocalRange);
```







