


# CommonCdnAuthParamTooLong constant







int const CommonCdnAuthParamTooLong
  




<p>Description: The Input CDN auth param is too long. <br>Cause: The length of auth parameter passed in when calling <code>enablePublishDirectToCDN</code> or <code>startPlayingStream</code> exceeds the limit. <br>Solutions: Auth param length should be less than 1024 bytes.</p>



## Implementation

```dart
static const int CommonCdnAuthParamTooLong = 1000019;
```







