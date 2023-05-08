


# getRoomBatchPropertiesStream method








Stream&lt;[ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent-class.md)> getRoomBatchPropertiesStream
()

_<span class="feature">inherited</span>_



<p>get room batch properties notifier</p>



## Implementation

```dart
Stream<ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent>
    getRoomBatchPropertiesStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getRoomPropertiesBatchUpdatedEventStream();
}
```







