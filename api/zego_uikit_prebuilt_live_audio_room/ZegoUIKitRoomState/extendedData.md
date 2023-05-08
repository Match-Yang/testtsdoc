


# extendedData property







Map&lt;String, dynamic> extendedData
  
_<span class="feature">read / write</span>_



<p>Extended Information with state updates. When the room login is successful, the key "room_session_id" can be used to obtain the unique RoomSessionID of each audio and video communication, which identifies the continuous communication from the first user in the room to the end of the audio and video communication. It can be used in scenarios such as call quality scoring and call problem diagnosis.</p>



## Implementation

```dart
Map<String, dynamic> extendedData;
```







