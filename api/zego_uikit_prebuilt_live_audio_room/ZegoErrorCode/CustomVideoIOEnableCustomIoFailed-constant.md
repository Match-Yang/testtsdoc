


# CustomVideoIOEnableCustomIoFailed constant







int const CustomVideoIOEnableCustomIoFailed
  




<p>Description: Failed to enable/disable custom video capture/rendering. <br>Cause: Not enable/disable custom video capture/rendering before engine is started. <br> Solutions: Please make sure to enable/disable custom video capture/rendering before engine is started, i.e., before calling (startPreview), (startPublishingStream), (startPlayingStream), (createMediaPlayer) or (createAudioEffectPlayer).</p>



## Implementation

```dart
static const int CustomVideoIOEnableCustomIoFailed = 1011003;
```







