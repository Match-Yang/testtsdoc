


# unloadResource method








Future&lt;void> unloadResource
(int audioEffectID)





<p>Unload audio effect resource.</p>
<p>Available since: 1.16.0
Description: Unload the specified audio effect resource.
When to call: After the sound effects are used up, related resources can be released through this function; otherwise, the SDK will release the loaded resources when the AudioEffectPlayer instance is destroyed.
Restrictions: None.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/loadResource.md">loadResource</a>.</p>
<ul>
<li><code>audioEffectID</code> ID for the audio effect loaded.</li>
</ul>



## Implementation

```dart
Future<void> unloadResource(int audioEffectID);
```







