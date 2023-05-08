


# MixerInputImageUrlFormatError constant







int const MixerInputImageUrlFormatError
  




<p>Description: Failed to mix stream input image. <br>Cause: The image format of the mixed stream input parameter is incorrect. <br>Solution: Use JPG and PNG formats. There are 2 ways to use it: 1. URI: Provide the picture to ZEGO technical support for configuration. After the configuration is complete, the picture URI will be provided, for example: preset-id://xxx.jpg. 2. URL: Only HTTP protocol is supported.</p>



## Implementation

```dart
static const int MixerInputImageUrlFormatError = 1005035;
```







