


# getInvitationReceivedStream method








Stream&lt;Map&lt;String, dynamic>> getInvitationReceivedStream
()

_<span class="feature">inherited</span>_



<p>stream callback, notify invitee when call invitation received</p>



## Implementation

```dart
Stream<Map<String, dynamic>> getInvitationReceivedStream() {
  return ZegoSignalingPluginCore
      .shared.coreData.streamCtrlInvitationReceived.stream;
}
```







