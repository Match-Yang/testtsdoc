


# setPlaySpeed method








Future&lt;void> setPlaySpeed
(double speed)





<p>Set the speed of play.</p>
<p>Available since: 2.12.0
Description: Set the playback speed of the player.
When to call: You should load resource before invoking this function.
Restrictions: None.
Related APIs: Resources can be loaded through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResource.md">loadResource</a> function.</p>
<ul>
<li><code>speed</code> The speed of play. The range is 0.5 ~ 2.0. The default is 1.0.</li>
</ul>



## Implementation

```dart
Future<void> setPlaySpeed(double speed);
```







