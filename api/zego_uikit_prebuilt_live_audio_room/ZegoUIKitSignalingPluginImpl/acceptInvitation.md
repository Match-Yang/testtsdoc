


# acceptInvitation method








Future&lt;[ZegoSignalingPluginResponseInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)> acceptInvitation
({required String inviterID, required String data})

_<span class="feature">inherited</span>_



<p>invitee accept the call invitation
<code>inviterID</code> inviter id, who send invitation
<code>data</code> extended field</p>



## Implementation

```dart
Future<ZegoSignalingPluginResponseInvitationResult> acceptInvitation({
  required String inviterID,
  required String data,
}) async {
  final invitationID = ZegoSignalingPluginCore.shared.coreData
      .queryInvitationIDByInviterID(inviterID);
  debugPrint(
      'accept invitation: invitationID:$invitationID, inviter id:$inviterID, data:$data');

  if (invitationID.isEmpty) {
    debugPrint('[Error] invitationID is empty');
    return const ZegoSignalingPluginResponseInvitationResult();
  }

  return ZegoSignalingPluginCore.shared.coreData.accept(invitationID, data);
}
```







