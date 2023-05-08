


# refuseInvitationByInvitationID method








Future&lt;[ZegoSignalingPluginResponseInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)> refuseInvitationByInvitationID
({required String invitationID, required String data})

_<span class="feature">inherited</span>_






## Implementation

```dart
Future<ZegoSignalingPluginResponseInvitationResult>
    refuseInvitationByInvitationID({
  required String invitationID,
  required String data,
}) async {
  debugPrint('refuse invitation: invitationID:$invitationID, data:$data');

  if (invitationID.isEmpty) {
    debugPrint('[Error] invitationID is empty');
    return const ZegoSignalingPluginResponseInvitationResult();
  }

  return ZegoSignalingPluginCore.shared.coreData.reject(invitationID, data);
}
```







