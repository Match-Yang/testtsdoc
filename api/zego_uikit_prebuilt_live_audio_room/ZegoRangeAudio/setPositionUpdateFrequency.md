


# setPositionUpdateFrequency method








Future&lt;void> setPositionUpdateFrequency
(int frequency)





<p>Set the frequency of real-time update locations within the SDK.</p>
<p>Available since: 2.21.0
Description: Set the frequency of real-time update locations within the SDK min 15 ms.
Use case: After setting the update position, the sensitivity of audio gradient is very high.
Default value: 100 ms.
When to call: After initializing the range audio <code>createRangeAudio</code>.</p>
<ul>
<li><code>frequency</code> the frequency, the value must be greater than 15 ms.</li>
</ul>



## Implementation

```dart
Future<void> setPositionUpdateFrequency(int frequency);
```







