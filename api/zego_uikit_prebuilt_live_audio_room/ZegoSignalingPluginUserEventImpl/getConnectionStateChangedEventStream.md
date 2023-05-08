


# getConnectionStateChangedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginConnectionStateChangedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginConnectionStateChangedEvent-class.md)> getConnectionStateChangedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginConnectionStateChangedEvent>
    getConnectionStateChangedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .connectionStateChangedEvent
      .stream;
}
```







