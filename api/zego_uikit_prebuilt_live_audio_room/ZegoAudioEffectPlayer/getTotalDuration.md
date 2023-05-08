


# getTotalDuration method








Future&lt;int> getTotalDuration
(int audioEffectID)





<p>Get the total duration of the specified audio effect resource.</p>
<p>Available since: 1.16.0
Description: Get the total duration of the specified audio effect resource. Unit is millisecond.
When to call: You should invoke this function after the audio effect resource already loaded, otherwise the return value is 0.
Restrictions: It can be called after <code>createAudioEffectPlayer</code>.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/start.md">start</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/loadResource.md">loadResource</a>.</p>
<ul>
<li><code>audioEffectID</code> ID for the audio effect.</li>
<li>Returns Unit is millisecond.</li>
</ul>



## Implementation

```dart
Future<int> getTotalDuration(int audioEffectID);
```







