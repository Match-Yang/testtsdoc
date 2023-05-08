


# CommonCdnUrlTooLong constant







int const CommonCdnUrlTooLong
  




<p>Description: The Input CDN URL is too long. <br>Cause: The length of URL parameter passed in when calling <code>enablePublishDirectToCDN</code> or <code>startPlayingStream</code> exceeds the limit. <br>Solutions: URL length should be less than 1024 bytes.</p>



## Implementation

```dart
static const int CommonCdnUrlTooLong = 1000018;
```







