


# enableFrequencySpectrumMonitor method








Future&lt;void> enableFrequencySpectrumMonitor
(bool enable, int millisecond)





<p>Whether to enable frequency spectrum monitoring.</p>
<p>Available since: 2.15.0
Description: Whether to enable frequency spectrum monitoring.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Restrictions: None.
Related APIs: After it is turned on, user can use the <code>onMediaPlayerFrequencySpectrumUpdate</code> callback to monitor frequency spectrum updates.</p>
<ul>
<li><code>enable</code> Whether to enable monitoring, true is enabled, false is disabled.</li>
<li><code>millisecond</code> Monitoring time period of the frequency spectrum, in milliseconds, has a value range of <code>100, 3000</code>.</li>
</ul>



## Implementation

```dart
Future<void> enableFrequencySpectrumMonitor(bool enable, int millisecond);
```







