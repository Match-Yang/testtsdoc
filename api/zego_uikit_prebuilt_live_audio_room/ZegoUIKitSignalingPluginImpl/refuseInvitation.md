


# refuseInvitation method








Future&lt;[ZegoSignalingPluginResponseInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)> refuseInvitation
({required String inviterID, required String data})

_<span class="feature">inherited</span>_



<p>invitee reject the call invitation
<code>inviterID</code> inviter id, who send invitation
<code>data</code> extended field, you can include your reasons such as Declined</p>



## Implementation

```dart
Future<ZegoSignalingPluginResponseInvitationResult> refuseInvitation({
  required String inviterID,
  required String data,
}) async {
  var invitationID = '';
  Map<String, dynamic>? extendedDataMap;
  try {
    extendedDataMap = jsonDecode(data) as Map<String, dynamic>?;
  } catch (e) {
    debugPrint('refuse invitation, data is not a json:$data');
  } finally {
    if (extendedDataMap?.containsKey('invitation_id') ?? false) {
      invitationID = extendedDataMap!['invitation_id']! as String;
    } else {
      invitationID = ZegoSignalingPluginCore.shared.coreData
          .queryInvitationIDByInviterID(inviterID);
    }
  }

  debugPrint('refuse invitation: invitationID:$invitationID, '
      'inviter id:$inviterID, data:$data');

  if (invitationID.isEmpty) {
    debugPrint('[Error] invitationID is empty');
    return const ZegoSignalingPluginResponseInvitationResult();
  }

  return ZegoSignalingPluginCore.shared.coreData.reject(invitationID, data);
}
```







