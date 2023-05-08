


# updateSelfPosition method








Future&lt;void> updateSelfPosition
(Float32List position, Float32List axisForward, Float32List axisRight, Float32List axisUp)





<p>Update self position and orentation.</p>
<p>Available since: 2.11.0
Description: Update the user's position and orientation so that the SDK can calculate the distance between the user and the audio source and the stereo effect of the left and right ears.
Use case: When the role operated by the user in the game moves on the world map, the position information and head orientation of the role are updated.
When to call: Called after logging in to the room <code>loginRoom</code>.
Caution: Before calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/enableSpeaker.md">enableSpeaker</a> to turn on the speaker, if you do not call this interface to set the location information, you will not be able to receive voices from other people except the team.</p>
<ul>
<li><code>position</code> The coordinates of the oneself in the world coordinate system. The parameter is a float array of length 3. The three values ​​represent the front, right, and top coordinate values ​​in turn.</li>
<li><code>axisForward</code> The unit vector of the front axis of its own coordinate system. The parameter is a float array with a length of 3. The three values ​​represent the front, right, and top coordinate values ​​in turn.</li>
<li><code>axisRight</code> The unit vector of the right axis of its own coordinate system. The parameter is a float array with a length of 3. The three values ​​represent the front, right, and top coordinate values ​​in turn.</li>
<li><code>axisUp</code> The unit vector of the up axis of its own coordinate system. The parameter is a float array with a length of 3. The three values ​​represent the front, right, and top coordinate values ​​in turn.</li>
</ul>



## Implementation

```dart
Future<void> updateSelfPosition(Float32List position, Float32List axisForward,
    Float32List axisRight, Float32List axisUp);
```







