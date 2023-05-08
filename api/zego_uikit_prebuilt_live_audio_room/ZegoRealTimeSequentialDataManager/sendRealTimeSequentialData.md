


# sendRealTimeSequentialData method








Future&lt;[ZegoRealTimeSequentialDataSentResult](../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataSentResult-class.md)> sendRealTimeSequentialData
(Uint8List data, String streamID)





<p>Send real-time sequential data to the broadcasting stream ID.</p>
<p>Available since: 2.14.0
Description: This function can be used to send real-time sequential data on the stream currently being broadcast.
Use cases: You need to call this function when you need to send real-time sequential data.
When to call: After calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager/startBroadcasting.md">startBroadcasting</a>.
Restrictions: None.
Caution: None.</p>
<ul>
<li><code>data</code> The real-time sequential data to be sent.</li>
<li><code>streamID</code> The stream ID to which the real-time sequential data is sent.</li>
<li>Returns Send real-time sequential data result notification.</li>
</ul>



## Implementation

```dart
Future<ZegoRealTimeSequentialDataSentResult> sendRealTimeSequentialData(
    Uint8List data, String streamID);
```







