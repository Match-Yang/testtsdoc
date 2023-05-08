


# stopScore method








Future&lt;int> stopScore
(String resourceID)





<p>Stop scoring.</p>
<p>Available since: 2.15.0
Description: End the current rating.The <code>OnCurrentPitchValueUpdate</code> callback will be stopped, but the average or total score can still be obtained normally.
Use case: You can call this interface to end the scoring while scoring.
When to call: It can be called while grading.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the accompaniment or accompaniment clip.</li>
</ul>



## Implementation

```dart
Future<int> stopScore(String resourceID);
```







