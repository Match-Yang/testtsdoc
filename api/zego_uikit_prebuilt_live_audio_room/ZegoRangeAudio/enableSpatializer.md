


# enableSpatializer method








Future&lt;void> enableSpatializer
(bool enable)





<p>Turn the 3D spatial sound on or off.</p>
<p>Available since: 2.11.0
Description: After the 3D sound effect is turned on, the sound effect in the actual space will be simulated according to the position of the speaker equivalent to the listener. The intuitive feeling is that the sound size and the left and right sound difference will also change when the distance and orientation of the sound source change.
Use case: It is a feature of audio recognition in FPS games or social scene games.
Default value: When this function is not called, 3D sound effects are turned off by default.
When to call: After initializing the range audio <code>createRangeAudio</code>.
Caution: The 3D audio effect will only take effect when <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setRangeAudioMode.md">setRangeAudioMode</a> is called and set to <code>World</code> mode.
Related APIs: After enabling the 3D sound effect, you can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/updateAudioSource.md">updateAudioSource</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/updateSelfPosition.md">updateSelfPosition</a> to change the position and orientation to experience the 3D effect.</p>
<ul>
<li><code>enable</code> Whether to enable 3D sound effects.</li>
</ul>



## Implementation

```dart
Future<void> enableSpatializer(bool enable);
```







