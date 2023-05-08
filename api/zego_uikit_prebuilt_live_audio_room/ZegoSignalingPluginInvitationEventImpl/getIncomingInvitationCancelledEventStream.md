


# getIncomingInvitationCancelledEventStream method







- @override

Stream&lt;[ZegoSignalingPluginIncomingInvitationCancelledEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationCancelledEvent-class.md)> getIncomingInvitationCancelledEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginIncomingInvitationCancelledEvent>
    getIncomingInvitationCancelledEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .incomingInvitationCancelledEvent
      .stream;
}
```







