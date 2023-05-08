


# updateAudioSource method








Future&lt;void> updateAudioSource
(String userID, Float32List position)





<p>Add or update audio source position information.</p>
<p>Available since: 2.11.0
Description: Set the position of the audio source corresponding to the userID on the game map in the room, so that the SDK can calculate the distance and orientation of the listener to the audio source.
Use case: Update the position of the voice user in the game map coordinates.
When to call: Call <code>loginRoom</code> to call after logging in to the room, and the recorded audio source information will be cleared after logging out of the room.</p>
<ul>
<li><code>userID</code> The userID of the sound source.</li>
<li><code>position</code> The coordinates of the speaker in the world coordinate system. The parameter is a float array of length 3. The three values ​​represent the front, right, and top coordinate values ​​in turn.</li>
</ul>



## Implementation

```dart
Future<void> updateAudioSource(String userID, Float32List position);
```







