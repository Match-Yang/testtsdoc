


# CommonStreamIdTooLong constant







int const CommonStreamIdTooLong
  




<p>Description: The input streamID is too long. <br>Cause: The length of the streamID parameter passed in when calling <code>startPublishingStream</code> or <code>startPlayingStream</code> exceeds the limit. <br>Solutions: The streamID should be less than 256 bytes.</p>



## Implementation

```dart
static const int CommonStreamIdTooLong = 1000014;
```







