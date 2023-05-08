


# getCurrentPitch method








Future&lt;int> getCurrentPitch
(String resourceID)





<p>Get real-time pitch data.</p>
<p>Available since: 2.15.0
Description: Get real-time pitch data.
Use case: Can be used to display real-time pitch lines on the view.
When to call: It can be called after playing the copyright accompaniment or accompaniment clip and starting to score.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the song or accompaniment.</li>
</ul>



## Implementation

```dart
Future<int> getCurrentPitch(String resourceID);
```







