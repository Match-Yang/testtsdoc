


# ZegoInnerText constructor







ZegoInnerText({String? takeSeatMenuButton, String? disagreeButton, String? agreeButton, String? removeSpeakerMenuDialogButton, String? muteSpeakerMenuDialogButton, String? cancelMenuDialogButton, String? memberListTitle, String? memberListRoleYou, String? memberListRoleHost, String? memberListRoleSpeaker, String? removeSpeakerFailedToast, String? messageEmptyToast, String? applyToTakeSeatButton, String? cancelTheTakeSeatApplicationButton, String? memberListAgreeButton, String? memberListDisagreeButton, String? inviteToTakeSeatMenuDialogButton, [ZegoDialogInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? cameraPermissionSettingDialogInfo, [ZegoDialogInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? microphonePermissionSettingDialogInfo, [ZegoDialogInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? removeFromSeatDialogInfo, [ZegoDialogInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? leaveSeatDialogInfo, [ZegoDialogInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? hostInviteTakeSeatDialog, String? audioEffectTitle, String? audioEffectReverbTitle, String? audioEffectVoiceChangingTitle, String? voiceChangerNoneTitle, String? voiceChangerLittleBoyTitle, String? voiceChangerLittleGirlTitle, String? voiceChangerDeepTitle, String? voiceChangerCrystalClearTitle, String? voiceChangerRobotTitle, String? voiceChangerEtherealTitle, String? voiceChangerFemaleTitle, String? voiceChangerMaleTitle, String? voiceChangerOptimusPrimeTitle, String? voiceChangerCMajorTitle, String? voiceChangerAMajorTitle, String? voiceChangerHarmonicMinorTitle, String? reverbTypeNoneTitle, String? reverbTypeKTVTitle, String? reverbTypeHallTitle, String? reverbTypeConcertTitle, String? reverbTypeRockTitle, String? reverbTypeSmallRoomTitle, String? reverbTypeLargeRoomTitle, String? reverbTypeValleyTitle, String? reverbTypeRecordingStudioTitle, String? reverbTypeBasementTitle, String? reverbTypePopularTitle, String? reverbTypeGramophoneTitle})





## Implementation

```dart
ZegoInnerText({
  String? takeSeatMenuButton,
  String? disagreeButton,
  String? agreeButton,
  String? removeSpeakerMenuDialogButton,
  String? muteSpeakerMenuDialogButton,
  String? cancelMenuDialogButton,
  String? memberListTitle,
  String? memberListRoleYou,
  String? memberListRoleHost,
  String? memberListRoleSpeaker,
  String? removeSpeakerFailedToast,
  String? messageEmptyToast,
  String? applyToTakeSeatButton,
  String? cancelTheTakeSeatApplicationButton,
  String? memberListAgreeButton,
  String? memberListDisagreeButton,
  String? inviteToTakeSeatMenuDialogButton,
  ZegoDialogInfo? cameraPermissionSettingDialogInfo,
  ZegoDialogInfo? microphonePermissionSettingDialogInfo,
  ZegoDialogInfo? removeFromSeatDialogInfo,
  ZegoDialogInfo? leaveSeatDialogInfo,
  ZegoDialogInfo? hostInviteTakeSeatDialog,
  String? audioEffectTitle,
  String? audioEffectReverbTitle,
  String? audioEffectVoiceChangingTitle,
  String? voiceChangerNoneTitle,
  String? voiceChangerLittleBoyTitle,
  String? voiceChangerLittleGirlTitle,
  String? voiceChangerDeepTitle,
  String? voiceChangerCrystalClearTitle,
  String? voiceChangerRobotTitle,
  String? voiceChangerEtherealTitle,
  String? voiceChangerFemaleTitle,
  String? voiceChangerMaleTitle,
  String? voiceChangerOptimusPrimeTitle,
  String? voiceChangerCMajorTitle,
  String? voiceChangerAMajorTitle,
  String? voiceChangerHarmonicMinorTitle,
  String? reverbTypeNoneTitle,
  String? reverbTypeKTVTitle,
  String? reverbTypeHallTitle,
  String? reverbTypeConcertTitle,
  String? reverbTypeRockTitle,
  String? reverbTypeSmallRoomTitle,
  String? reverbTypeLargeRoomTitle,
  String? reverbTypeValleyTitle,
  String? reverbTypeRecordingStudioTitle,
  String? reverbTypeBasementTitle,
  String? reverbTypePopularTitle,
  String? reverbTypeGramophoneTitle,
})  : takeSeatMenuButton = takeSeatMenuButton ?? 'Take the seat',
      disagreeButton = disagreeButton ?? 'Disagree',
      agreeButton = agreeButton ?? 'Agree',
      removeSpeakerMenuDialogButton =
          removeSpeakerMenuDialogButton ?? 'Remove %0 from seat',
      muteSpeakerMenuDialogButton = muteSpeakerMenuDialogButton ?? 'Mute %0',
      cancelMenuDialogButton = cancelMenuDialogButton ?? 'Cancel',
      memberListTitle = memberListTitle ?? 'Audience',
      memberListRoleYou = memberListRoleYou ?? 'You',
      memberListRoleHost = memberListRoleHost ?? 'Host',
      memberListRoleSpeaker = memberListRoleSpeaker ?? 'Speaker',
      removeSpeakerFailedToast =
          removeSpeakerFailedToast ?? 'Failed to remove %0 from seat',
      messageEmptyToast = messageEmptyToast ?? 'Say something...',
      applyToTakeSeatButton = applyToTakeSeatButton ?? 'Apply to take seat',
      cancelTheTakeSeatApplicationButton =
          cancelTheTakeSeatApplicationButton ?? 'Cancel',
      memberListAgreeButton = memberListAgreeButton ?? 'Agree',
      memberListDisagreeButton = memberListDisagreeButton ?? 'Disagree',
      inviteToTakeSeatMenuDialogButton =
          inviteToTakeSeatMenuDialogButton ?? 'Invite %0 to take seat',
      cameraPermissionSettingDialogInfo = cameraPermissionSettingDialogInfo ??
          ZegoDialogInfo(
            title: 'Can not use Camera!',
            message: 'Please enable camera access in the system settings!',
            cancelButtonName: 'Cancel',
            confirmButtonName: 'Settings',
          ),
      microphonePermissionSettingDialogInfo =
          microphonePermissionSettingDialogInfo ??
              ZegoDialogInfo(
                title: 'Can not use Microphone!',
                message:
                    'Please enable microphone access in the system settings!',
                cancelButtonName: 'Cancel',
                confirmButtonName: 'Settings',
              ),
      removeFromSeatDialogInfo = removeFromSeatDialogInfo ??
          ZegoDialogInfo(
            title: 'Remove the speaker',
            message: 'Are you sure to remove %0 from the seat?',
            cancelButtonName: 'Cancel',
            confirmButtonName: 'OK',
          ),
      leaveSeatDialogInfo = leaveSeatDialogInfo ??
          ZegoDialogInfo(
            title: 'Leave the seat',
            message: 'Are you sure to leave seat?',
            cancelButtonName: 'Cancel',
            confirmButtonName: 'OK',
          ),
      hostInviteTakeSeatDialog = hostInviteTakeSeatDialog ??
          ZegoDialogInfo(
            title: 'Invitation',
            message: 'The host is inviting you to take seat',
            cancelButtonName: 'Disagree',
            confirmButtonName: 'Agree',
          ),
      audioEffectTitle = audioEffectTitle ?? 'Audio effect',
      audioEffectReverbTitle = audioEffectReverbTitle ?? 'Reverb',
      audioEffectVoiceChangingTitle =
          audioEffectVoiceChangingTitle ?? 'Voice changing',
      voiceChangerNoneTitle = voiceChangerNoneTitle ?? 'None',
      voiceChangerLittleBoyTitle = voiceChangerLittleBoyTitle ?? 'Little boy',
      voiceChangerLittleGirlTitle =
          voiceChangerLittleGirlTitle ?? 'Little girl',
      voiceChangerDeepTitle = voiceChangerDeepTitle ?? 'Deep',
      voiceChangerCrystalClearTitle =
          voiceChangerCrystalClearTitle ?? 'Crystal-clear',
      voiceChangerRobotTitle = voiceChangerRobotTitle ?? 'Robot',
      voiceChangerEtherealTitle = voiceChangerEtherealTitle ?? 'Ethereal',
      voiceChangerFemaleTitle = voiceChangerFemaleTitle ?? 'Female',
      voiceChangerMaleTitle = voiceChangerMaleTitle ?? 'Male',
      voiceChangerOptimusPrimeTitle =
          voiceChangerOptimusPrimeTitle ?? 'Optimus Prime',
      voiceChangerCMajorTitle = voiceChangerCMajorTitle ?? 'C major',
      voiceChangerAMajorTitle = voiceChangerAMajorTitle ?? 'A major',
      voiceChangerHarmonicMinorTitle =
          voiceChangerHarmonicMinorTitle ?? 'Harmonic minor',
      reverbTypeNoneTitle = reverbTypeNoneTitle ?? 'None',
      reverbTypeKTVTitle = reverbTypeKTVTitle ?? 'Karaoke',
      reverbTypeHallTitle = reverbTypeHallTitle ?? 'Hall',
      reverbTypeConcertTitle = reverbTypeConcertTitle ?? 'Concert',
      reverbTypeRockTitle = reverbTypeRockTitle ?? 'Rock',
      reverbTypeSmallRoomTitle = reverbTypeSmallRoomTitle ?? 'Small room',
      reverbTypeLargeRoomTitle = reverbTypeLargeRoomTitle ?? 'Large room',
      reverbTypeValleyTitle = reverbTypeValleyTitle ?? 'Valley',
      reverbTypeRecordingStudioTitle =
          reverbTypeRecordingStudioTitle ?? 'Recording studio',
      reverbTypeBasementTitle = reverbTypeBasementTitle ?? 'Basement',
      reverbTypePopularTitle = reverbTypePopularTitle ?? 'Pop',
      reverbTypeGramophoneTitle = reverbTypeGramophoneTitle ?? 'Gramophone';
```







