


# IMManagerCreationFailed constant







int const IMManagerCreationFailed
  




<p>Description: The real-time sequential data manager instance creation failed. <br>Cause: A manager instance with this room ID has already been created. <br>Solution: A maximum of 1 instance can be created for each room ID. If you need to create multiple instances, please use other room IDs.</p>



## Implementation

```dart
static const int IMManagerCreationFailed = 1009031;
```







