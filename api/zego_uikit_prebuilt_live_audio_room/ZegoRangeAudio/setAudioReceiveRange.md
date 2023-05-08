


# setAudioReceiveRange method








Future&lt;void> setAudioReceiveRange
(double range)





<p>Set the maximum range of received audio.</p>
<p>Available since: 2.11.0
Description: Set the audio receiving range, the audio source sound beyond this range will not be received.
Use case: Set the receiver's receiving range in the <code>World</code> mode.
Default value: When this function is not called, there is no distance limit, and everyone in the room can be received.
When to call: After initializing the range audio <code>createRangeAudio</code>.
Restrictions: This range only takes effect for people outside the team.</p>
<ul>
<li><code>range</code> the audio range, the value must be greater than or equal to 0.</li>
</ul>



## Implementation

```dart
Future<void> setAudioReceiveRange(double range);
```







