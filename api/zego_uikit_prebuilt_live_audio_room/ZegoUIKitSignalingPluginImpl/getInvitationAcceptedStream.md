


# getInvitationAcceptedStream method








Stream&lt;Map&lt;String, dynamic>> getInvitationAcceptedStream
()

_<span class="feature">inherited</span>_



<p>stream callback, notify when call invitation accepted by invitee</p>



## Implementation

```dart
Stream<Map<String, dynamic>> getInvitationAcceptedStream() {
  return ZegoSignalingPluginCore
      .shared.coreData.streamCtrlInvitationAccepted.stream;
}
```







