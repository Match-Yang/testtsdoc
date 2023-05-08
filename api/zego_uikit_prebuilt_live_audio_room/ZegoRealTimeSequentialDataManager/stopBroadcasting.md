


# stopBroadcasting method








Future&lt;void> stopBroadcasting
(String streamID)





<p>Stop broadcasting real-time sequential data stream.</p>
<p>Available since: 2.14.0
Description: This function allows users to stop broadcasting their local real-time sequential data stream.
Use cases: When you no longer need to send real-time sequential data, you need to call this function to stop broadcasting.
When to call: After creating the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md">ZegoRealTimeSequentialDataManager</a> instance.
Restrictions: None.
Caution: After calling this function, you will receive the <code>onPublisherStateUpdate</code> callback to tell you the broadcast state (publish state) of this stream. After stopping the broadcast, other users in the same room will receive the <code>onRoomStreamUpdate</code> callback to tell them this stream has been deleted from the room.</p>
<ul>
<li><code>streamID</code> The ID of the stream that needs to stop broadcasting.</li>
</ul>



## Implementation

```dart
Future<void> stopBroadcasting(String streamID);
```







