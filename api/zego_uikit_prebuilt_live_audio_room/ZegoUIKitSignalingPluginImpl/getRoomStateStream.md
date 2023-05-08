


# getRoomStateStream method








Stream&lt;[ZegoSignalingPluginRoomStateChangedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomStateChangedEvent-class.md)> getRoomStateStream
()








## Implementation

```dart
Stream<ZegoSignalingPluginRoomStateChangedEvent> getRoomStateStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getRoomStateChangedEventStream();
}
```







