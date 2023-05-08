


# updateStreamPosition method








Future&lt;void> updateStreamPosition
(String streamID, Float32List position)





<p>Update the location of the flow.</p>
<p>Available since: 2.23.0
Description: Set range voice volume.
Use case: When the user calls <code>startPlayingStream</code> to pull another stream, call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setStreamVocalRange.md">setStreamVocalRange</a> to set the stream's voice position, then call this interface to set the stream's position, so that the stream also has the range voice effect.
When to call: After initializing the range audio <code>createRangeAudio</code> and after <code>startPlayingStream</code>.</p>
<ul>
<li><code>streamID</code> play stream id.</li>
<li><code>position</code> The unit vector of the front axis of its own coordinate system. The parameter is a float array with a length of 3. The three values ​​represent the front, right, and top coordinate values ​​in turn.</li>
</ul>



## Implementation

```dart
Future<void> updateStreamPosition(String streamID, Float32List position);
```







