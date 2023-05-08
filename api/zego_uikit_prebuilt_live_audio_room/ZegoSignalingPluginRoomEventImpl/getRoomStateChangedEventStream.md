


# getRoomStateChangedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginRoomStateChangedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomStateChangedEvent-class.md)> getRoomStateChangedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginRoomStateChangedEvent>
    getRoomStateChangedEventStream() {
  return ZegoSignalingPluginCore().eventCenter.roomStateChangedEvent.stream;
}
```







