


# getConnectionStateStream method








Stream&lt;[ZegoSignalingPluginConnectionStateChangedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginConnectionStateChangedEvent-class.md)> getConnectionStateStream
()








## Implementation

```dart
Stream<ZegoSignalingPluginConnectionStateChangedEvent>
    getConnectionStateStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getConnectionStateChangedEventStream();
}
```







