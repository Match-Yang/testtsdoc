


# getInvitationCanceledStream method








Stream&lt;Map&lt;String, dynamic>> getInvitationCanceledStream
()

_<span class="feature">inherited</span>_



<p>stream callback, notify when call invitation cancelled by inviter</p>



## Implementation

```dart
Stream<Map<String, dynamic>> getInvitationCanceledStream() {
  return ZegoSignalingPluginCore
      .shared.coreData.streamCtrlInvitationCanceled.stream;
}
```







