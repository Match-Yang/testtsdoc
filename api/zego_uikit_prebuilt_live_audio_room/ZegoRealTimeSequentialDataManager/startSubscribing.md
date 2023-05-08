


# startSubscribing method








Future&lt;void> startSubscribing
(String streamID)





<p>Start subscribing real-time sequential data stream.</p>
<p>Available since: 2.14.0
Description: This function allows users to subscribe to the real-time sequential data stream of remote users from the ZEGO RTC server.
Use cases: When you need to receive real-time sequential data sent from other remote users, you need to call this function to start subscribing to the stream broadcasted by other remote users.
When to call: After creating the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md">ZegoRealTimeSequentialDataManager</a> instance.
Restrictions: None.
Caution: After calling this function, you will receive the <code>onPlayerStateUpdate</code> callback to tell you the subscribe state (play state) of this stream.</p>
<ul>
<li><code>streamID</code> Stream ID, a string of up to 256 characters.
Caution:
<ol>
<li>Only support numbers, English characters and '-', '&nbsp;'.</li>
</ol>
</li>
</ul>



## Implementation

```dart
Future<void> startSubscribing(String streamID);
```







