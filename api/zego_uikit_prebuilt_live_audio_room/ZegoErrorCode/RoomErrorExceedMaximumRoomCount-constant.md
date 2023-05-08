


# RoomErrorExceedMaximumRoomCount constant







int const RoomErrorExceedMaximumRoomCount
  




<p>Description: in test environment The total number of rooms logged in at the same time exceeds the limit. (In the test environment, the maximum number of concurrent rooms is 10). <br>Cause: Too many rooms logged in at the same time. <br> Solutions: logout some room, login room.</p>



## Implementation

```dart
static const int RoomErrorExceedMaximumRoomCount = 1002035;
```







