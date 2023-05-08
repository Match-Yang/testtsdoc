


# getOutgoingInvitationAcceptedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginOutgoingInvitationAcceptedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationAcceptedEvent-class.md)> getOutgoingInvitationAcceptedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginOutgoingInvitationAcceptedEvent>
    getOutgoingInvitationAcceptedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .outgoingInvitationAcceptedEvent
      .stream;
}
```







