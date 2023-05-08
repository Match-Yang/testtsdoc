


# MediaPlayerPlatformFormatNotSupported constant







int const MediaPlayerPlatformFormatNotSupported
  




<p>Description: The MediaPlayer is configured with a video data format not supported by the platform. <br>Cause: The MediaPlayer is configured with a video data format not supported by the platform (e.g., CVPixelBuffer on iOS does not support NV21). <br> Solutions: Check the data format <code>setVideoHandler</code> supported by the current media player platform and set the correct data format.</p>



## Implementation

```dart
static const int MediaPlayerPlatformFormatNotSupported = 1008020;
```







