


# enableSoundLevelMonitor method








Future&lt;void> enableSoundLevelMonitor
(bool enable, int millisecond)





<p>Whether to enable sound level monitoring.</p>
<p>Available since: 2.15.0
Description: Whether to enable sound level monitoring.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Restrictions: None.
Related callbacks: After it is turned on, user can use the <code>onMediaPlayerSoundLevelUpdate</code> callback to monitor sound level updates.</p>
<ul>
<li><code>enable</code> Whether to enable monitoring, true is enabled, false is disabled.</li>
<li><code>millisecond</code> Monitoring time period of the sound level, in milliseconds, has a value range of <code>100, 3000</code>.</li>
</ul>



## Implementation

```dart
Future<void> enableSoundLevelMonitor(bool enable, int millisecond);
```







