


# loadResource method








Future&lt;[ZegoAudioEffectPlayerLoadResourceResult](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayerLoadResourceResult-class.md)> loadResource
(int audioEffectID, String path)





<p>Load audio effect resource.</p>
<p>Available since: 1.16.0
Description: Load audio effect resource.
Use cases: In a scene where the same sound effect is played frequently, the SDK provides the function of preloading the sound effect file into the memory in order to optimize the performance of repeatedly reading and decoding the file.
When to call: It can be called after <code>createAudioEffectPlayer</code>.
Restrictions: Preloading supports loading up to 15 sound effect files at the same time, and the duration of the sound effect files cannot exceed 30s, otherwise an error will be reported when loading.</p>
<ul>
<li><code>audioEffectID</code> ID for the audio effect.</li>
<li><code>path</code> the absolute path or "assets://" of the audio effect resource and cannot be null or "". <br>Value range: "ipod-library://" and network url are not supported.</li>
<li>Returns Result for audio effect player loads resources</li>
</ul>



## Implementation

```dart
Future<ZegoAudioEffectPlayerLoadResourceResult> loadResource(
    int audioEffectID, String path);
```







