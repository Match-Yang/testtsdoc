


# startBroadcasting method








Future&lt;void> startBroadcasting
(String streamID)





<p>Start broadcasting real-time sequential data stream.</p>
<p>Available since: 2.14.0
Description: This function allows users to broadcast their local real-time sequential data stream to the ZEGO RTC server, and other users in the same room can subscribe to the real-time sequential data stream for intercommunication through "streamID".
Use cases: Before sending real-time sequential data, you need to call this function to start broadcasting.
When to call: After creating the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md">ZegoRealTimeSequentialDataManager</a> instance.
Restrictions: None.
Caution: After calling this function, you will receive the <code>onPublisherStateUpdate</code> callback to tell you the broadcast state (publish state) of this stream. After the broadcast is successful, other users in the same room will receive the <code>onRoomStreamUpdate</code> callback to tell them this stream has been added to the room.</p>
<ul>
<li><code>streamID</code> Stream ID, a string of up to 256 characters.
Caution:
<ol>
<li>Need to be globally unique within the entire AppID (Note that it cannot be the same as the stream ID passed in <code>startPublishingStream</code>). If in the same AppID, different users publish each stream and the stream ID is the same, which will cause the user to publish the stream failure. You cannot include URL keywords, otherwise publishing stream and playing stream will fails.</li>
<li>Only support numbers, English characters and '-', '&nbsp;'.</li>
</ol>
</li>
</ul>



## Implementation

```dart
Future<void> startBroadcasting(String streamID);
```







