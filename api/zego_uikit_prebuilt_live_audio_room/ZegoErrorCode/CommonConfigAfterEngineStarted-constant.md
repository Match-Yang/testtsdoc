


# CommonConfigAfterEngineStarted constant







int const CommonConfigAfterEngineStarted
  




<p>Description: The engine audio and video module has been activated, and this setting is not supported. <br>Cause: Only supports setting before starting the audio and video module of the engine. <br>Solutions: Please set it before calling <code>startPreviewView</code> <code>startPublishingStream</code> <code>startPlayingStream</code> to start the audio and video module.</p>



## Implementation

```dart
static const int CommonConfigAfterEngineStarted = 1000066;
```







