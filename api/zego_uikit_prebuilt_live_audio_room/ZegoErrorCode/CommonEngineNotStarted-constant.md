


# CommonEngineNotStarted constant







int const CommonEngineNotStarted
  




<p>Description: The audio and video module of the engine is not started and cannot support function realization. <br>Cause: Audio and video modules with no engine started.<br>Solutions: Please call <code>startPreviewView</code> <code>startPublishingStream</code> <code>startPlayingStream</code> to start the audio and video module first.</p>



## Implementation

```dart
static const int CommonEngineNotStarted = 1000003;
```







