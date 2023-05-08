


# ZegoUIKitPrebuiltLiveAudioRoomConfig constructor







ZegoUIKitPrebuiltLiveAudioRoomConfig({bool turnOnMicrophoneWhenJoining = true, bool useSpeakerWhenJoining = true, bool closeSeatsWhenJoining = true, [ZegoLiveAudioRoomSeatConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomSeatConfig-class.md)? seatConfig, [ZegoTopMenuBarConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoTopMenuBarConfig-class.md)? topMenuBarConfig, [ZegoBottomMenuBarConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoBottomMenuBarConfig-class.md)? bottomMenuBarConfig, [ZegoLiveAudioRoomLayoutConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomLayoutConfig-class.md)? layoutConfig, [ZegoInRoomMessageViewConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessageViewConfig-class.md)? messageConfig, [ZegoAudioEffectConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectConfig-class.md)? effectConfig, List&lt;int> hostSeatIndexes = const [0], [ZegoDialogInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? confirmDialogInfo, Future&lt;bool> onLeaveConfirmation(BuildContext context)?, VoidCallback? onLeaveLiveAudioRoom, Widget? background, String? userAvatarUrl, Map&lt;String, String> userInRoomAttributes = const {}, void onUserCountOrPropertyChanged(List&lt;[ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> users)?, VoidCallback? onSeatClosed, VoidCallback? onSeatsOpened, void onSeatClicked(int index, [ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)? user)?, void onSeatsChanged(Map&lt;int, [ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> takenSeats, List&lt;int> untakenSeats)?, void onSeatTakingRequested([ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) audience)?, void onSeatTakingRequestCanceled([ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) audience)?, VoidCallback? onInviteAudienceToTakeSeatFailed, VoidCallback? onSeatTakingInviteRejected, VoidCallback? onSeatTakingRequestFailed, VoidCallback? onSeatTakingRequestRejected, VoidCallback? onHostSeatTakingInviteSent, void onMemberListMoreButtonPressed([ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) user)?, [ZegoInnerText](../../zego_uikit_prebuilt_live_audio_room/ZegoInnerText-class.md)? translationText})





## Implementation

```dart
ZegoUIKitPrebuiltLiveAudioRoomConfig({
  this.turnOnMicrophoneWhenJoining = true,
  this.useSpeakerWhenJoining = true,
  this.closeSeatsWhenJoining = true,
  ZegoLiveAudioRoomSeatConfig? seatConfig,
  ZegoTopMenuBarConfig? topMenuBarConfig,
  ZegoBottomMenuBarConfig? bottomMenuBarConfig,
  ZegoLiveAudioRoomLayoutConfig? layoutConfig,
  ZegoInRoomMessageViewConfig? messageConfig,
  ZegoAudioEffectConfig? effectConfig,
  this.hostSeatIndexes = const [0],
  this.confirmDialogInfo,
  this.onLeaveConfirmation,
  this.onLeaveLiveAudioRoom,
  this.background,
  this.userAvatarUrl,
  this.userInRoomAttributes = const {},
  this.onUserCountOrPropertyChanged,
  this.onSeatClosed,
  this.onSeatsOpened,
  this.onSeatClicked,
  this.onSeatsChanged,
  this.onSeatTakingRequested,
  this.onSeatTakingRequestCanceled,
  this.onInviteAudienceToTakeSeatFailed,
  this.onSeatTakingInviteRejected,
  this.onSeatTakingRequestFailed,
  this.onSeatTakingRequestRejected,
  this.onHostSeatTakingInviteSent,
  this.onMemberListMoreButtonPressed,
  ZegoInnerText? translationText,
})  : seatConfig = seatConfig ?? ZegoLiveAudioRoomSeatConfig(),
      topMenuBarConfig = topMenuBarConfig ?? ZegoTopMenuBarConfig(),
      bottomMenuBarConfig = bottomMenuBarConfig ?? ZegoBottomMenuBarConfig(),
      layoutConfig = layoutConfig ?? ZegoLiveAudioRoomLayoutConfig(),
      inRoomMessageViewConfig =
          messageConfig ?? ZegoInRoomMessageViewConfig(),
      audioEffectConfig = effectConfig ?? ZegoAudioEffectConfig(),
      innerText = translationText ?? ZegoInnerText();
```







