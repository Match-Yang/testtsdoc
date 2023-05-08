


# getInRoomTextMessageReceivedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginInRoomTextMessageReceivedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInRoomTextMessageReceivedEvent-class.md)> getInRoomTextMessageReceivedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginInRoomTextMessageReceivedEvent>
    getInRoomTextMessageReceivedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .inRoomTextMessageReceived
      .stream;
}
```







