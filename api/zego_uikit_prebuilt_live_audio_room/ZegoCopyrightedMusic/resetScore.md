


# resetScore method








Future&lt;int> resetScore
(String resourceID)





<p>Reset scoring.</p>
<p>Available since: 2.15.0
Description: Reset the scores that have already been performed,The <code>OnCurrentPitchValueUpdate</code> callback will be stopped and the average or total score will be 0.
Use case: Often used in scenes where the same song is re-sung.
When to call: It can be called after scoring has been performed.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the accompaniment or accompaniment clip.</li>
</ul>



## Implementation

```dart
Future<int> resetScore(String resourceID);
```







