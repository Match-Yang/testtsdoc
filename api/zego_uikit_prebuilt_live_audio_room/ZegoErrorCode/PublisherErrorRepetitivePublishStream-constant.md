


# PublisherErrorRepetitivePublishStream constant







int const PublisherErrorRepetitivePublishStream
  




<p>Description: Failed to publish the stream. The same stream already exists in the room.<br>Cause: The same stream already exists in the room.<br>Solutions: Replace with a new stream ID. Adjust the stream ID generation strategy to ensure uniqueness.</p>



## Implementation

```dart
static const int PublisherErrorRepetitivePublishStream = 1003028;
```







