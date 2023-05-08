


# getInvitationRefusedStream method








Stream&lt;Map&lt;String, dynamic>> getInvitationRefusedStream
()

_<span class="feature">inherited</span>_



<p>stream callback, notify when call invitation rejected by invitee</p>



## Implementation

```dart
Stream<Map<String, dynamic>> getInvitationRefusedStream() {
  return ZegoSignalingPluginCore
      .shared.coreData.streamCtrlInvitationRefused.stream;
}
```







