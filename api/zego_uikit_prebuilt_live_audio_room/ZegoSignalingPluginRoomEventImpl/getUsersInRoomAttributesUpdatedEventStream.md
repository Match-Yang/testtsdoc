


# getUsersInRoomAttributesUpdatedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent-class.md)> getUsersInRoomAttributesUpdatedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent>
    getUsersInRoomAttributesUpdatedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .usersInRoomAttributesUpdatedEvent
      .stream;
}
```







