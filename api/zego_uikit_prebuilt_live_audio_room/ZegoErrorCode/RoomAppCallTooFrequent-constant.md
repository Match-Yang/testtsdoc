


# RoomAppCallTooFrequent constant







int const RoomAppCallTooFrequent
  




<p>Description: Room signalling type interfaces are called more frequently than the upper limit. <br>Cause: This application calls the room signalling type interface too often. (e.g., <code>sendCustomCommand</code> <code>sendBroadcastMessage</code>) <br>Solutions: Please control the frequency of application calls to the room signalling type interface. Please refer to <a href="https://docs.zegocloud.com/article/7612">https://docs.zegocloud.com/article/7612</a> for details.</p>



## Implementation

```dart
static const int RoomAppCallTooFrequent = 1002073;
```







