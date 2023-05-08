


# cancelInvitation method








Future&lt;[ZegoSignalingPluginCancelInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCancelInvitationResult-class.md)> cancelInvitation
({required List&lt;String> invitees, required String data})

_<span class="feature">inherited</span>_



<p>cancel invitation to one or more specified users
<code>inviteeID</code> invitee's id
<code>data</code> extended field</p>



## Implementation

```dart
Future<ZegoSignalingPluginCancelInvitationResult> cancelInvitation({
  required List<String> invitees,
  required String data,
}) async {
  invitees.removeWhere((item) => ['', null].contains(item));
  if (invitees.isEmpty) {
    debugPrint('[Error] invitees is empty');
    return ZegoSignalingPluginCancelInvitationResult(
        error: PlatformException(code: '', message: ''),
        errorInvitees: <String>[]);
  }

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
          .queryInvitationIDByInvitees(invitees);
    }
  }

  debugPrint('cancel invitation: invitationID:$invitationID, '
      'invitees:$invitees, data:$data');

  return ZegoSignalingPluginCore.shared.coreData
      .cancel(invitees, invitationID, data);
}
```







