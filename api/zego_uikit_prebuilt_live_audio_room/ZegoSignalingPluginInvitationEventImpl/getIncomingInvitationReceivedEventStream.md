


# getIncomingInvitationReceivedEventStream method







- @override

Stream&lt;[ZegoSignalingPluginIncomingInvitationReceivedEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationReceivedEvent-class.md)> getIncomingInvitationReceivedEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginIncomingInvitationReceivedEvent>
    getIncomingInvitationReceivedEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .incomingInvitationReceivedEvent
      .stream;
}
```







