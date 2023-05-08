


# PlayerErrorPlayStreamWhenUsingMultiRoom constant







int const PlayerErrorPlayStreamWhenUsingMultiRoom
  




<p>Description: Calling the wrong function after enabling the multi-room function causes playing stream fail. <br>Cause: Called the playing stream function that only works for joining a single room mode. <br>Solutions: Please use the function of the same name with ZegoPlayerConfig and specify the room ID to play the stream.</p>



## Implementation

```dart
static const int PlayerErrorPlayStreamWhenUsingMultiRoom = 1004070;
```







