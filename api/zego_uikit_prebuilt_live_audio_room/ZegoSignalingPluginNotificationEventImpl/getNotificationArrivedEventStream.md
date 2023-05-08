


# getNotificationArrivedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginNotificationArrivedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationArrivedEvent-class.md)> getNotificationArrivedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginNotificationArrivedEvent>
    getNotificationArrivedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .notificationArrivedEvent
      .stream;
}
```







