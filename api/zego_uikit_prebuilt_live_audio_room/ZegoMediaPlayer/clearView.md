


# clearView method








Future&lt;void> clearView
()





<p>Clears the last frame of the playback control that remains on the control after playback ends.</p>
<p>Available since: 2.20.0
Description: Clears the last frame of the playback control that remains on the control after playback ends.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Restrictions: The interface call takes effect only when the media player ends playing.</p>



## Implementation

```dart
Future<void> clearView();
```







