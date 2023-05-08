


# RoomCountExceed constant







int const RoomCountExceed
  




<p>Description: The number of rooms the user attempted to log into simultaneously exceeds the maximum number allowed. Currently, a user can only be logged in to one main room.<br>Cause: In single-room mode, log in to multiple main rooms at the same time (including repeated calls to log in to the same room A without exiting room A). <br>Solutions: Please check is login multiple rooms simultaneously or not under single room mode.</p>



## Implementation

```dart
static const int RoomCountExceed = 1002001;
```







