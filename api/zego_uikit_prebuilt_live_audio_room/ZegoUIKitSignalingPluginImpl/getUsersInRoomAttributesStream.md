


# getUsersInRoomAttributesStream method








Stream&lt;[ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent-class.md)> getUsersInRoomAttributesStream
()

_<span class="feature">inherited</span>_



<p>get users in-room attributes notifier</p>



## Implementation

```dart
Stream<ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent>
    getUsersInRoomAttributesStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getUsersInRoomAttributesUpdatedEventStream();
}
```







