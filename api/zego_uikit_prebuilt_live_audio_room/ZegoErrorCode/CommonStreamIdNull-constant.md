


# CommonStreamIdNull constant







int const CommonStreamIdNull
  




<p>Description: The input StreamID is null. <br>Cause: The streamID parameter passed in when calling <code>startPublishingStream</code> or <code>startPlayingStream</code> is null or empty string. <br>Solutions: Check whether the streamID parameter passed in when calling the function is normal.</p>



## Implementation

```dart
static const int CommonStreamIdNull = 1000015;
```







