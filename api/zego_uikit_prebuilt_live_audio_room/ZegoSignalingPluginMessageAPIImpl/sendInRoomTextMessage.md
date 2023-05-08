


# sendInRoomTextMessage method







- @override

Future&lt;[ZegoSignalingPluginInRoomTextMessageResult](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInRoomTextMessageResult-class.md)> sendInRoomTextMessage
({required String roomID, required String message})

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<ZegoSignalingPluginInRoomTextMessageResult> sendInRoomTextMessage(
    {required String roomID, required String message}) {
  return ZIM
      .getInstance()!
      .sendMessage(
        ZIMTextMessage(message: message),
        roomID,
        ZIMConversationType.room,
        ZIMMessageSendConfig(),
      )
      .then((ZIMMessageSentResult zimResult) {
    return const ZegoSignalingPluginInRoomTextMessageResult();
  }).catchError((error) {
    ZegoSignalingLoggerService.logInfo(
      'send in-room text message, error:${error.toString()}',
      tag: 'signaling',
      subTag: 'room',
    );

    return ZegoSignalingPluginInRoomTextMessageResult(
      error: error,
    );
  });
}
```







