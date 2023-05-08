


# CustomVideoIONotSupportedBufferType constant







int const CustomVideoIONotSupportedBufferType
  




<p>Description: Custom video rendering does not support the currently set video buffer type. <br>Cause: The buffer_type in the config parameter of <code>enableCustomVideoRender</code> only supports raw_data, cv_pixel_buffer, encoded_data. For <code>enableCustomVideoProcessing</code>, only raw_data is supported on Windows platform, only cv_pixel_buffer is supported on Apple devices, and gl_texture_2d and surface_texture are supported on Android platform. <br> Solutions: Select the correct video buffer type.</p>



## Implementation

```dart
static const int CustomVideoIONotSupportedBufferType = 1011011;
```







