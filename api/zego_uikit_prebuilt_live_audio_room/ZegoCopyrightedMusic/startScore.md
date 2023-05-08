


# startScore method








Future&lt;int> startScore
(String resourceID, int pitchValueInterval)





<p>Start scoring.</p>
<p>Available since: 2.15.0
Description: Start the scoring function.After starting scoring, the scoring result OnCurrentPitchValueUpdate callback will be received according to the set callback time interval.
Use case: Can be used to display the singing score on the view.
When to call: After obtaining krc verbatim lyrics and playing the accompaniment resources of copyrighted music.
Restrictions: Only support use this api after <code>startPublishingStream</code>.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the accompaniment or accompaniment clip.</li>
<li><code>pitchValueInterval</code> the time interval of real-time pitch line callback, in milliseconds, the default is 50 milliseconds.</li>
</ul>



## Implementation

```dart
Future<int> startScore(String resourceID, int pitchValueInterval);
```







