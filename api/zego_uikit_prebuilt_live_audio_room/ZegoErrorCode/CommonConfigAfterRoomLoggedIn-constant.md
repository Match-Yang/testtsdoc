


# CommonConfigAfterRoomLoggedIn constant







int const CommonConfigAfterRoomLoggedIn
  




<p>Description: The room is logged in, this setting is not supported. <br>Cause: Only supports setting before logging into the room. <br>Solutions: Please set it before calling <code>loginRoom</code> or after calling <code>logoutRoom</code>. Note that if you log in to multiple rooms, you need to log out of all rooms before setting.</p>



## Implementation

```dart
static const int CommonConfigAfterRoomLoggedIn = 1000067;
```







