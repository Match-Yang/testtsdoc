


# PublisherBitrateInvalid constant







int const PublisherBitrateInvalid
  




<p>Description: Publishing failed due to wrong bitrate setting.<br>Cause: The set video bitrate, audio bitrate, or minimum video bitrate threshold for traffic control exceeds the upper limit.<br>Solutions: Please check if the bitrate value is in the correct unit (kbps).Adjust the bitrate setting.</p>



## Implementation

```dart
static const int PublisherBitrateInvalid = 1003002;
```







