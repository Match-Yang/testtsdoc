


# getNotificationRegisteredEventStream method







- @override

Stream&lt;[ZegoSignalingPluginNotificationRegisteredEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationRegisteredEvent-class.md)> getNotificationRegisteredEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginNotificationRegisteredEvent>
    getNotificationRegisteredEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .notificationRegisteredEvent
      .stream;
}
```







