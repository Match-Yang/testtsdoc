


# getRoomPropertiesStream method








Stream&lt;[ZegoSignalingPluginRoomPropertiesUpdatedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesUpdatedEvent-class.md)> getRoomPropertiesStream
()

_<span class="feature">inherited</span>_



<p>get room properties notifier</p>



## Implementation

```dart
Stream<ZegoSignalingPluginRoomPropertiesUpdatedEvent>
    getRoomPropertiesStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getRoomPropertiesUpdatedEventStream();
}
```







