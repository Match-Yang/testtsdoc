


# onMixerSoundLevelUpdate property







(void Function(Map&lt;int, double> soundLevels)?) onMixerSoundLevelUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the sound level of any input stream changes in the stream mixing process.</p>
<p>Available since: 1.2.1
Description: Developers can use this callback to display the effect of which stream’s anchor is talking on the UI interface of the mixed stream of the audience.
Use cases: It is often used when multiple video images are required to synthesize a video using mixed streaming, such as education, live teacher and student images.
When to trigger: After the developer calls the <code>startPlayingStream</code> function to start playing the mixed stream. Callback notification period is 100 ms.
Restrictions: The callback is triggered every 100 ms, and the trigger frequency cannot be set.Due to the high frequency of this callback, please do not perform time-consuming tasks or UI operations in this callback to avoid stalling.
Related callbacks: <code>OnMixerRelayCDNStateUpdate</code> can be used to get update notification of mixing stream repost CDN status.
Related APIs: Develop can start a mixed flow task through <code>startMixerTask</code>.</p>
<ul>
<li><code>soundLevels</code> The sound key-value pair of each single stream in the mixed stream, the key is the soundLevelID of each single stream, and the value is the sound value of the corresponding single stream. Value range: The value range of value is 0.0 ~ 100.0.</li>
</ul>



## Implementation

```dart
static void Function(Map<int, double> soundLevels)? onMixerSoundLevelUpdate;
```







