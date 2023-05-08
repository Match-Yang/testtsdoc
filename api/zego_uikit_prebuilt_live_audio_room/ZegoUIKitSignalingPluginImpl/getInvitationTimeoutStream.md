


# getInvitationTimeoutStream method








Stream&lt;Map&lt;String, dynamic>> getInvitationTimeoutStream
()

_<span class="feature">inherited</span>_



<p>stream callback, notify invitee if invitation timeout</p>



## Implementation

```dart
Stream<Map<String, dynamic>> getInvitationTimeoutStream() {
  return ZegoSignalingPluginCore
      .shared.coreData.streamCtrlInvitationTimeout.stream;
}
```







