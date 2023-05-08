


# getRoomPropertiesUpdatedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginRoomPropertiesUpdatedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesUpdatedEvent-class.md)> getRoomPropertiesUpdatedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginRoomPropertiesUpdatedEvent>
    getRoomPropertiesUpdatedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .roomPropertiesUpdatedEvent
      .stream;
}
```







