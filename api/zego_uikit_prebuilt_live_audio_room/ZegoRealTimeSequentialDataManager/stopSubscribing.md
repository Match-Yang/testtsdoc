


# stopSubscribing method








Future&lt;void> stopSubscribing
(String streamID)





<p>Stop subscribing real-time sequential data stream.</p>
<p>Available since: 2.14.0
Description: This function can be used to stop subscribing to the real-time sequential data stream.
Use cases: When you no longer need to receive real-time sequential data sent by other users, you need to call this function to stop subscribing to the other user's stream.
When to call: After creating the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md">ZegoRealTimeSequentialDataManager</a> instance.
Restrictions: None.
Caution: After calling this function, you will receive the <code>onPlayerStateUpdate</code> callback to tell you the subscribe state (play state) of this stream.</p>
<ul>
<li><code>streamID</code> The ID of the stream that needs to stop subscribing.</li>
</ul>



## Implementation

```dart
Future<void> stopSubscribing(String streamID);
```







