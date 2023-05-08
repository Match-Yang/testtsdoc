


# onRoomOnlineUserCountUpdate property







(void Function(String roomID, int count)?) onRoomOnlineUserCountUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered every 30 seconds to report the current number of online users.</p>
<p>Available since: 1.7.0
Description: This method will notify the user of the current number of online users in the room..
Use cases: Developers can use this callback to show the number of user online in the current room.
When to call /Trigger: After successfully logging in to the room.
Restrictions: None.
Caution: 1. This function is called back every 30 seconds. 2. Because of this design, when the number of users in the room exceeds 500, there will be some errors in the statistics of the number of online people in the room.</p>
<ul>
<li><code>roomID</code> Room ID where the user is logged in, a string of up to 128 bytes in length.</li>
<li><code>count</code> Count of online users.</li>
</ul>



## Implementation

```dart
static void Function(String roomID, int count)? onRoomOnlineUserCountUpdate;
```







