


# onSeatsChanged property







(void Function(Map&lt;int, [ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> takenSeats, List&lt;int> untakenSeats)?) onSeatsChanged
  
_<span class="feature">read / write</span>_



<p>A callback function that is called when someone gets on/off/switches seat</p>
<p>The <code>takenSeats</code> parameter is a map that maps the index of each taken seat
to the user who is currently sitting in that seat.</p>
<p>The <code>untakenSeats</code> parameter is a list of the indexes of all untaken seats.</p>



## Implementation

```dart
void Function(
  Map<int, ZegoUIKitUser> takenSeats,
  List<int> untakenSeats,
)? onSeatsChanged;
```







