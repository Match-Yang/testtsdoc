


# getNotificationClickedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginNotificationClickedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationClickedEvent-class.md)> getNotificationClickedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginNotificationClickedEvent>
    getNotificationClickedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .notificationClickedEvent
      .stream;
}
```







