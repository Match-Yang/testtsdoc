


# PreprocessNotSupportEffectsBufferType constant







int const PreprocessNotSupportEffectsBufferType
  




<p>Description: Effects Beauty does not support the currently set video data type. <br>Cause: <code>enableCustomVideoProcessing</code> interface, Windows platform only supports raw_data, Apple device only supports cv_pixel_buffer, Android platform supports gl_texture_2d. <br>Solutions: select the correct video data type.</p>



## Implementation

```dart
static const int PreprocessNotSupportEffectsBufferType = 1007023;
```







