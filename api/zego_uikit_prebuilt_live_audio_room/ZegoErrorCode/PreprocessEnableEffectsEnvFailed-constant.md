


# PreprocessEnableEffectsEnvFailed constant







int const PreprocessEnableEffectsEnvFailed
  




<p>Description: Failed to open or close the beauty environment. <br>Cause: The beauty environment was not turned on or off before the engine started. <br>Solutions: Please make sure to turn on or turn off the beauty environment before the engine starts, for example: before calling (startPreview), (startPublishingStream), (startPlayingStream), (createMediaPlayer) or (createAudioEffectPlayer).</p>



## Implementation

```dart
static const int PreprocessEnableEffectsEnvFailed = 1007020;
```







