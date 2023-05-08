


# getCurrentProgress method








Future&lt;int> getCurrentProgress
(int audioEffectID)





<p>Get current playback progress.</p>
<p>Available since: 1.16.0
Description: Get current playback progress of the specified audio effect. Unit is millisecond.
When to call: You should invoke this function after the audio effect resource already loaded, otherwise the return value is 0.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/start.md">start</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/loadResource.md">loadResource</a>.</p>
<ul>
<li><code>audioEffectID</code> ID for the audio effect.</li>
</ul>



## Implementation

```dart
Future<int> getCurrentProgress(int audioEffectID);
```







