


# setRangeAudioVolume method








Future&lt;void> setRangeAudioVolume
(int volume)





<p>Set range voice volume.</p>
<p>Available since: 2.23.0
Description: Set range voice volume.
Use case: This interface allows you to increase or decrease the volume of a range voice stream when the user calls <code>startPlayingStream</code> and pulls another stream.
Default value: 100.
When to call: After initializing the range audio <code>createRangeAudio</code>.</p>
<ul>
<li><code>volume</code> volume, <code>0,200</code>.</li>
</ul>



## Implementation

```dart
Future<void> setRangeAudioVolume(int volume);
```







