


# RoomMultiRoomSwtichRoomInvalid constant







int const RoomMultiRoomSwtichRoomInvalid
  




<p>Description: The <code>switchRoom</code> function cannot be used in multi-room mode. <br>Cause: multi room mode SDK not support. <br> Solutions: first call <code>logoutRoom</code> then call <code>loginRoom</code>.</p>



## Implementation

```dart
static const int RoomMultiRoomSwtichRoomInvalid = 1002019;
```







