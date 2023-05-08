


# getInRoomTextMessageReceivedEventStream method








Stream&lt;[ZegoSignalingPluginInRoomTextMessageReceivedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInRoomTextMessageReceivedEvent-class.md)> getInRoomTextMessageReceivedEventStream
()

_<span class="feature">inherited</span>_






## Implementation

```dart
Stream<ZegoSignalingPluginInRoomTextMessageReceivedEvent>
    getInRoomTextMessageReceivedEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getInRoomTextMessageReceivedEventStream();
}
```







