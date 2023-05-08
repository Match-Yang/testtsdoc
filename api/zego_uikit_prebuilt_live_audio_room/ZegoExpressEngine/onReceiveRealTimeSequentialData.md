


# onReceiveRealTimeSequentialData property







(void Function([ZegoRealTimeSequentialDataManager](../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md) manager, Uint8List data, String streamID)?) onReceiveRealTimeSequentialData
  
_<span class="feature">read / write</span>_



<p>Callback for receiving real-time sequential data.</p>
<p>Available since: 2.14.0
Description: Through this callback, you can receive real-time sequential data from the current subscribing stream.
Use cases: You need to listen to this callback when you need to receive real-time sequential data.
When to trigger: After calling <code>startSubscribing</code> to successfully start the subscription, and when data is sent on the stream, this callback will be triggered.
Restrictions: None.
Caution: None.</p>
<ul>
<li><code>manager</code> The real-time sequential data manager instance that triggers this callback.</li>
<li><code>data</code> The received real-time sequential data.</li>
<li><code>streamID</code> Subscribed stream ID</li>
</ul>



## Implementation

```dart
static void Function(ZegoRealTimeSequentialDataManager manager,
    Uint8List data, String streamID)? onReceiveRealTimeSequentialData;
```







