


# MediaPlayerTakeSnapshotTimingError constant







int const MediaPlayerTakeSnapshotTimingError
  




<p>Description: takeSnapshot screenshot failed <br>Cause: The video is not playing or 'setPlayerCanvas' is not called to display the video to the control. <br>Solutions: Check whether the video plays normally(check <code>onPlayStart</code> callback) and the screen is displayed normally.</p>



## Implementation

```dart
static const int MediaPlayerTakeSnapshotTimingError = 1008042;
```







