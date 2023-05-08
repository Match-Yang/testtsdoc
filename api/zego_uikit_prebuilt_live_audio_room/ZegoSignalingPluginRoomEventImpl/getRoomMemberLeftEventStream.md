


# getRoomMemberLeftEventStream method







- @override

Stream&lt;[ZegoSignalingPluginRoomMemberLeftEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomMemberLeftEvent-class.md)> getRoomMemberLeftEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginRoomMemberLeftEvent>
    getRoomMemberLeftEventStream() {
  return ZegoSignalingPluginCore().eventCenter.roomMemberLeftEvent.stream;
}
```







