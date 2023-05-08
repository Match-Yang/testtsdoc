


# getBackgroundThroughMessageReceivedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginThroughMessageReceivedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginThroughMessageReceivedEvent-class.md)> getBackgroundThroughMessageReceivedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginThroughMessageReceivedEvent>
    getBackgroundThroughMessageReceivedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .throughMessageReceivedEvent
      .stream;
}
```







