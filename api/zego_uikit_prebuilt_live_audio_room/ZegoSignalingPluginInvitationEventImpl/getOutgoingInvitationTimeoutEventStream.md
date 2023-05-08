


# getOutgoingInvitationTimeoutEventStream method







- @override

Stream&lt;[ZegoSignalingPluginOutgoingInvitationTimeoutEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationTimeoutEvent-class.md)> getOutgoingInvitationTimeoutEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginOutgoingInvitationTimeoutEvent>
    getOutgoingInvitationTimeoutEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .outgoingInvitationTimeoutEvent
      .stream;
}
```







