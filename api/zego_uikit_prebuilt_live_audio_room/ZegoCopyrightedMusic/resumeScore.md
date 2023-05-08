


# resumeScore method








Future&lt;int> resumeScore
(String resourceID)





<p>Resume scoring.</p>
<p>Available since: 2.15.0
Description: Resume currently paused scoring.
Use case: When there is currently paused scoring, this interface can be called to resume the scoring function.
When to call: It can be called when there is currently a paused scoring.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the accompaniment or accompaniment clip.</li>
</ul>



## Implementation

```dart
Future<int> resumeScore(String resourceID);
```







