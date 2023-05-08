


# getPreviousScore method








Future&lt;int> getPreviousScore
(String resourceID)





<p>Get the score of the previous sentence.</p>
<p>Available since: 2.15.0
Description: Get the score of the previous sentence.
Use case: Can be used to display the score of each sentence on the view.
When to call: It can be called after playing the copyright accompaniment or accompaniment clip and starting to score.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the accompaniment or accompaniment clip.</li>
</ul>



## Implementation

```dart
Future<int> getPreviousScore(String resourceID);
```







