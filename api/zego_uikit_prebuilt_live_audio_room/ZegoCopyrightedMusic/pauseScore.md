


# pauseScore method








Future&lt;int> pauseScore
(String resourceID)





<p>Pause scoring.</p>
<p>Available since: 2.15.0
Description: Pause ongoing scoring,will stop the <code>OnCurrentPitchValueUpdate</code> callback.
Use case: You can call this interface to pause the scoring function while scoring.
When to call: It can be called while grading.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the accompaniment or accompaniment clip.</li>
</ul>



## Implementation

```dart
Future<int> pauseScore(String resourceID);
```







