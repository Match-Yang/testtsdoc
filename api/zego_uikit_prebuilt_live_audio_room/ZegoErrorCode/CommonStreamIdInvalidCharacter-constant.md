


# CommonStreamIdInvalidCharacter constant







int const CommonStreamIdInvalidCharacter
  




<p>Description: The input streamID contains invalid characters. <br>Cause: The streamID parameter passed in when calling <code>startPublishingStream</code> or <code>startPlayingStream</code> contains invalid characters. <br>Solutions: Check whether the streamID parameter passed in when calling the function is normal, only support numbers, English characters and '-', '_'.</p>



## Implementation

```dart
static const int CommonStreamIdInvalidCharacter = 1000016;
```







