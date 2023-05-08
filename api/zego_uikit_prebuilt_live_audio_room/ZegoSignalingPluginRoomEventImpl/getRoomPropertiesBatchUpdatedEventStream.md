


# getRoomPropertiesBatchUpdatedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent-class.md)> getRoomPropertiesBatchUpdatedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent>
    getRoomPropertiesBatchUpdatedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .roomPropertiesBatchUpdatedEvent
      .stream;
}
```







