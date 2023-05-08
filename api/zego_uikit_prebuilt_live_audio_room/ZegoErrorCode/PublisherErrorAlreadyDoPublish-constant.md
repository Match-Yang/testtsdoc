


# PublisherErrorAlreadyDoPublish constant







int const PublisherErrorAlreadyDoPublish
  




<p>Description: Failed to publish the stream. The publish channel is already publishing streams.<br>Cause:  The publish channel is already publishing streams.<br>Solutions: Please check the business logic to avoid repeating the publish for publish channel which is publishing.</p>



## Implementation

```dart
static const int PublisherErrorAlreadyDoPublish = 1003023;
```







