


# setPlayStreamFocusOn method








Future&lt;void> setPlayStreamFocusOn
(String streamID)





<p>Set the weight of the pull stream priority.</p>
<p>Available since: 1.1.0
Description: Set the weight of the streaming priority.
Use cases: This interface can be used when developers need to prioritize the quality of a stream in business. For example: in class scene, if students pull multiple streams, you can set high priority for teacher stream.
When to call: after called <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/startPlayingStream.md">startPlayingStream</a>.
Restrictions: None.
Caution: By default, all streams have the same weight. Only one stream can be set with high priority, whichever is set last. After the flow is stopped, the initial state is automatically restored, and all flows have the same weight.When the local network is not good, while ensuring the focus flow, other stalls may be caused more.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
</ul>



## Implementation

```dart
Future<void> setPlayStreamFocusOn(String streamID) async {
  return await ZegoExpressImpl.instance.setPlayStreamFocusOn(streamID);
}
```







