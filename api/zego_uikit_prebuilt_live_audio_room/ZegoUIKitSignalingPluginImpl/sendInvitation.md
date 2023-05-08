


# sendInvitation method








Future&lt;[ZegoSignalingPluginSendInvitationResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSendInvitationResult-class.md)> sendInvitation
({required String inviterName, required List&lt;String> invitees, required int timeout, required int type, required String data, [ZegoNotificationConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoNotificationConfig-class.md)? zegoNotificationConfig})

_<span class="feature">inherited</span>_



<p>send invitation to one or more specified users
<code>invitees</code> list of invitees.
<code>timeout</code> timeout of the call invitation, the unit is seconds
<code>type</code> call type
<code>data</code> extended field, through which the inviter can carry information to the invitee.</p>



## Implementation

```dart
Future<ZegoSignalingPluginSendInvitationResult> sendInvitation({
  required String inviterName,
  required List<String> invitees,
  required int timeout,
  required int type,
  required String data,
  ZegoNotificationConfig? zegoNotificationConfig,
}) async {
  invitees.removeWhere((item) => ['', null].contains(item));
  if (invitees.isEmpty) {
    debugPrint('[Error] invitees is empty');
    return const ZegoSignalingPluginSendInvitationResult(
        invitationID: '', errorInvitees: {});
  }

  final zimExtendedData = const JsonEncoder().convert({
    'inviter_name': inviterName,
    'type': type,
    'data': data,
  });

  ZegoSignalingPluginNotificationConfig? pluginNotificationConfig;
  if (ZegoSignalingPluginCore
          .shared.coreData.notifyWhenAppIsInTheBackgroundOrQuit &&
      (zegoNotificationConfig?.notifyWhenAppIsInTheBackgroundOrQuit ??
          false)) {
    pluginNotificationConfig = ZegoSignalingPluginNotificationConfig(
      resourceID: zegoNotificationConfig!.resourceID,
      title: zegoNotificationConfig.title,
      message: zegoNotificationConfig.message,
      payload: zimExtendedData,
    );
  }

  debugPrint(
    'send invitation: invitees:$invitees, timeout:$timeout, type:$type, '
    'zimExtendedData:$zimExtendedData, '
    'notification config:$zegoNotificationConfig',
  );

  return ZegoSignalingPluginCore.shared.coreData.invite(
    invitees: invitees,
    type: type,
    timeout: timeout,
    zimExtendedData: zimExtendedData,
    kitData: data,
    notificationConfig: pluginNotificationConfig,
  );
}
```







