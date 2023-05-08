


# getRoomMemberJoinedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginRoomMemberJoinedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomMemberJoinedEvent-class.md)> getRoomMemberJoinedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginRoomMemberJoinedEvent>
    getRoomMemberJoinedEventStream() {
  return ZegoSignalingPluginCore().eventCenter.roomMemberJoinedEvent.stream;
}
```







