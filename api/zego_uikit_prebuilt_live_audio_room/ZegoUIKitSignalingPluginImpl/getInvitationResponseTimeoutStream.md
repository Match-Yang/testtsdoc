


# getInvitationResponseTimeoutStream method








Stream&lt;Map&lt;String, dynamic>> getInvitationResponseTimeoutStream
()

_<span class="feature">inherited</span>_



<p>stream callback, When the call invitation times out, the invitee does not respond, and the inviter will receive a callback.</p>



## Implementation

```dart
Stream<Map<String, dynamic>> getInvitationResponseTimeoutStream() {
  return ZegoSignalingPluginCore
      .shared.coreData.streamCtrlInvitationResponseTimeout.stream;
}
```







