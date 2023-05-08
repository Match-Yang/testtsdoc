


# getOutgoingInvitationRejectedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginOutgoingInvitationRejectedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationRejectedEvent-class.md)> getOutgoingInvitationRejectedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginOutgoingInvitationRejectedEvent>
    getOutgoingInvitationRejectedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .outgoingInvitationRejectedEvent
      .stream;
}
```







