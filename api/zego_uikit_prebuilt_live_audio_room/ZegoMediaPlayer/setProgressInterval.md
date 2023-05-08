


# setProgressInterval method








Future&lt;void> setProgressInterval
(int millisecond)





<p>Set playback progress callback interval.</p>
<p>This function can control the callback frequency of <code>onMediaPlayerPlayingProgress</code>. When the callback interval is set to 0, the callback is stopped. The default callback interval is 1s
This callback are not returned exactly at the set callback interval, but rather at the frequency at which the audio or video frames are processed to determine whether the callback is needed to call</p>
<ul>
<li><code>millisecond</code> Interval of playback progress callback in milliseconds</li>
</ul>



## Implementation

```dart
Future<void> setProgressInterval(int millisecond);
```







