


# ZegoInnerText class









<p>控制UI上文案
通过修改对应属性的值达到修改UI上文案的能力。当然你也可以改成其他语言
这个类被用于 ZegoUIKitPrebuiltLiveAudioRoomConfig.innerText 属性
注意，文案中的 %0 占位符会被替换成对应的用户名</p>




## Constructors

[ZegoInnerText](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/ZegoInnerText.md) ({String? takeSeatMenuButton, String? disagreeButton, String? agreeButton, String? removeSpeakerMenuDialogButton, String? muteSpeakerMenuDialogButton, String? cancelMenuDialogButton, String? memberListTitle, String? memberListRoleYou, String? memberListRoleHost, String? memberListRoleSpeaker, String? removeSpeakerFailedToast, String? messageEmptyToast, String? applyToTakeSeatButton, String? cancelTheTakeSeatApplicationButton, String? memberListAgreeButton, String? memberListDisagreeButton, String? inviteToTakeSeatMenuDialogButton, [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? cameraPermissionSettingDialogInfo, [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? microphonePermissionSettingDialogInfo, [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? removeFromSeatDialogInfo, [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? leaveSeatDialogInfo, [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? hostInviteTakeSeatDialog, String? audioEffectTitle, String? audioEffectReverbTitle, String? audioEffectVoiceChangingTitle, String? voiceChangerNoneTitle, String? voiceChangerLittleBoyTitle, String? voiceChangerLittleGirlTitle, String? voiceChangerDeepTitle, String? voiceChangerCrystalClearTitle, String? voiceChangerRobotTitle, String? voiceChangerEtherealTitle, String? voiceChangerFemaleTitle, String? voiceChangerMaleTitle, String? voiceChangerOptimusPrimeTitle, String? voiceChangerCMajorTitle, String? voiceChangerAMajorTitle, String? voiceChangerHarmonicMinorTitle, String? reverbTypeNoneTitle, String? reverbTypeKTVTitle, String? reverbTypeHallTitle, String? reverbTypeConcertTitle, String? reverbTypeRockTitle, String? reverbTypeSmallRoomTitle, String? reverbTypeLargeRoomTitle, String? reverbTypeValleyTitle, String? reverbTypeRecordingStudioTitle, String? reverbTypeBasementTitle, String? reverbTypePopularTitle, String? reverbTypeGramophoneTitle})

   


## Properties

##### [applyToTakeSeatButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/applyToTakeSeatButton.md) &#8596; String



观众申请连麦的按钮，默认值为 <code>Apply to take seat</code>  
_<span class="feature">read / write</span>_



##### [audioEffectReverbTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/audioEffectReverbTitle.md) &#8596; String



混响分类标题，默认值为 <code>Reverb</code>  
_<span class="feature">read / write</span>_



##### [audioEffectTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/audioEffectTitle.md) &#8596; String



音频特效对话框标题，默认值为 <code>Audio effect</code>  
_<span class="feature">read / write</span>_



##### [audioEffectVoiceChangingTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/audioEffectVoiceChangingTitle.md) &#8596; String



变声分类标题，默认值为 <code>Voice changing</code>  
_<span class="feature">read / write</span>_



##### [cameraPermissionSettingDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/cameraPermissionSettingDialogInfo.md) &#8596; [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)



摄像头权限设置的对话框，默认值为 <code>title: 'Can not use Camera!'</code>， <code>message: 'Please enable camera access in the system settings!'</code>， <code>cancelButtonName: 'Cancel'</code>， <code>confirmButtonName: 'Settings'</code>  
_<span class="feature">read / write</span>_



##### [cancelMenuDialogButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/cancelMenuDialogButton.md) &#8596; String



弹出式菜单的取消按钮，默认值为 <code>Cancel</code>  
_<span class="feature">read / write</span>_



##### [cancelTheTakeSeatApplicationButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/cancelTheTakeSeatApplicationButton.md) &#8596; String



观众取消申请连麦的按钮，默认值为  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [hostExtendButtonsWithIndex](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/hostExtendButtonsWithIndex.md) &#8596; List&lt;Map&lt;int, Widget>>



  
_<span class="feature">read / write</span>_



##### [hostInviteTakeSeatDialog](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/hostInviteTakeSeatDialog.md) &#8596; [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)



主播邀请观众上座后，观众收到的邀请对话框，默认值为 <code>title: 'Invitation'</code>， <code>message: 'The host is inviting you to take seat'</code>， <code>cancelButtonName: 'Disagree'</code>， <code>confirmButtonName: 'Agree'</code>  
_<span class="feature">read / write</span>_



##### [inviteToTakeSeatMenuDialogButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/inviteToTakeSeatMenuDialogButton.md) &#8596; String



主播点击成员列表上更多按钮时出现的邀请观众上座的按钮，默认值 'Invite %0 to take seat'  
_<span class="feature">read / write</span>_



##### [leaveSeatDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/leaveSeatDialogInfo.md) &#8596; [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)



Speaker主动离开座位前的确认对话框，默认值为 <code>title: 'Leave the seat'</code>， <code>message: 'Are you sure to leave seat?'</code>， <code>cancelButtonName: 'Cancel'</code>， <code>confirmButtonName: 'OK'</code>  
_<span class="feature">read / write</span>_



##### [memberListAgreeButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/memberListAgreeButton.md) &#8596; String



成员列表上接受观众申请上座的按钮，默认值为 <code>Agree</code>  
_<span class="feature">read / write</span>_



##### [memberListDisagreeButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/memberListDisagreeButton.md) &#8596; String



成员列表上拒绝观众申请上座的按钮，默认值为 <code>Disagree</code>  
_<span class="feature">read / write</span>_



##### [memberListRoleHost](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/memberListRoleHost.md) &#8596; String



成员列表中显示主播的标记，默认值是 <code>Host</code>  
_<span class="feature">read / write</span>_



##### [memberListRoleSpeaker](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/memberListRoleSpeaker.md) &#8596; String



成员列表中显示Speaker的标记，默认值是 <code>Speaker</code>  
_<span class="feature">read / write</span>_



##### [memberListRoleYou](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/memberListRoleYou.md) &#8596; String



成员列表中显示你自己的标记，默认值是 <code>You</code>  
_<span class="feature">read / write</span>_



##### [memberListTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/memberListTitle.md) &#8596; String



成员列表标题，默认值为 <code>Audience</code>  
_<span class="feature">read / write</span>_



##### [messageEmptyToast](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/messageEmptyToast.md) &#8596; String



聊天输入框没有内容时的提示，默认值为 <code>Say something...</code>  
_<span class="feature">read / write</span>_



##### [microphonePermissionSettingDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/microphonePermissionSettingDialogInfo.md) &#8596; [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)



麦克风权限设置的对话框，默认值为 <code>title: 'Can not use Microphone!'</code>， <code>message: 'Please enable microphone access in the system settings!'</code>， <code>cancelButtonName: 'Cancel'</code>， <code>confirmButtonName: 'Settings'</code>  
_<span class="feature">read / write</span>_



##### [muteSpeakerMenuDialogButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/muteSpeakerMenuDialogButton.md) &#8596; String



Host 点击座位上speaker弹出菜单项的将speaker静音按钮，默认值为 <code>Mute %0</code>  
_<span class="feature">read / write</span>_



##### [removeFromSeatDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/removeFromSeatDialogInfo.md) &#8596; [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)



主播将speaker移下座位前的确认对话框，默认值为 <code>title: 'Remove the speaker'</code>， <code>message: 'Are you sure to remove %0 from the seat?'</code>， <code>cancelButtonName: 'Cancel'</code>， <code>confirmButtonName: 'OK'</code>  
_<span class="feature">read / write</span>_



##### [removeSpeakerFailedToast](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/removeSpeakerFailedToast.md) &#8596; String



主播尝试将speaker移下座位失败的toast，默认值为 <code>Failed to remove %0 from seat</code>  
_<span class="feature">read / write</span>_



##### [removeSpeakerMenuDialogButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/removeSpeakerMenuDialogButton.md) &#8596; String



Host 点击座位上speaker弹出菜单项的将speaker移下座位按钮，默认值为 <code>Remove %0 from seat</code>  
_<span class="feature">read / write</span>_



##### [reverbTypeBasementTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeBasementTitle.md) &#8596; String



混响特效：Basement  
_<span class="feature">read / write</span>_



##### [reverbTypeConcertTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeConcertTitle.md) &#8596; String



混响特效：Concert  
_<span class="feature">read / write</span>_



##### [reverbTypeGramophoneTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeGramophoneTitle.md) &#8596; String



混响特效：Gramophone  
_<span class="feature">read / write</span>_



##### [reverbTypeHallTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeHallTitle.md) &#8596; String



混响特效：Hall  
_<span class="feature">read / write</span>_



##### [reverbTypeKTVTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeKTVTitle.md) &#8596; String



混响特效：Karaoke  
_<span class="feature">read / write</span>_



##### [reverbTypeLargeRoomTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeLargeRoomTitle.md) &#8596; String



混响特效：Large room  
_<span class="feature">read / write</span>_



##### [reverbTypeNoneTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeNoneTitle.md) &#8596; String



混响特效：None  
_<span class="feature">read / write</span>_



##### [reverbTypePopularTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypePopularTitle.md) &#8596; String



混响特效：Pop  
_<span class="feature">read / write</span>_



##### [reverbTypeRecordingStudioTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeRecordingStudioTitle.md) &#8596; String



混响特效：Recording studio  
_<span class="feature">read / write</span>_



##### [reverbTypeRockTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeRockTitle.md) &#8596; String



混响特效：Rock  
_<span class="feature">read / write</span>_



##### [reverbTypeSmallRoomTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeSmallRoomTitle.md) &#8596; String



混响特效：Small room  
_<span class="feature">read / write</span>_



##### [reverbTypeValleyTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/reverbTypeValleyTitle.md) &#8596; String



混响特效：Valley  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [takeSeatMenuButton](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/takeSeatMenuButton.md) &#8596; String



观众点击座位弹出的菜单上的申请上座按钮，默认值为 <code>Take the seat</code>  
_<span class="feature">read / write</span>_



##### [voiceChangerAMajorTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerAMajorTitle.md) &#8596; String



变声特效：A Major  
_<span class="feature">read / write</span>_



##### [voiceChangerCMajorTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerCMajorTitle.md) &#8596; String



变声特效：C Major  
_<span class="feature">read / write</span>_



##### [voiceChangerCrystalClearTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerCrystalClearTitle.md) &#8596; String



变声特效：Crystal-clear  
_<span class="feature">read / write</span>_



##### [voiceChangerDeepTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerDeepTitle.md) &#8596; String



变声特效：Deep  
_<span class="feature">read / write</span>_



##### [voiceChangerEtherealTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerEtherealTitle.md) &#8596; String



变声特效：Ethereal  
_<span class="feature">read / write</span>_



##### [voiceChangerFemaleTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerFemaleTitle.md) &#8596; String



变声特效：Female  
_<span class="feature">read / write</span>_



##### [voiceChangerHarmonicMinorTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerHarmonicMinorTitle.md) &#8596; String



变声特效：Harmonic minor  
_<span class="feature">read / write</span>_



##### [voiceChangerLittleBoyTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerLittleBoyTitle.md) &#8596; String



变声特效：Little Boy  
_<span class="feature">read / write</span>_



##### [voiceChangerLittleGirlTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerLittleGirlTitle.md) &#8596; String



变声特效：LittleGirl  
_<span class="feature">read / write</span>_



##### [voiceChangerMaleTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerMaleTitle.md) &#8596; String



变声特效：Male  
_<span class="feature">read / write</span>_



##### [voiceChangerNoneTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerNoneTitle.md) &#8596; String



变声特效：None  
_<span class="feature">read / write</span>_



##### [voiceChangerOptimusPrimeTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerOptimusPrimeTitle.md) &#8596; String



变声特效：Optimus Prime  
_<span class="feature">read / write</span>_



##### [voiceChangerRobotTitle](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/voiceChangerRobotTitle.md) &#8596; String



变声特效：Robot  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















