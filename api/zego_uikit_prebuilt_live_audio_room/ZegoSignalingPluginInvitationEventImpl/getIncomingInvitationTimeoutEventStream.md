


# getIncomingInvitationTimeoutEventStream method







- @override

Stream&lt;[ZegoSignalingPluginIncomingInvitationTimeoutEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationTimeoutEvent-class.md)> getIncomingInvitationTimeoutEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginIncomingInvitationTimeoutEvent>
    getIncomingInvitationTimeoutEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .incomingInvitationTimeoutEvent
      .stream;
}
```







