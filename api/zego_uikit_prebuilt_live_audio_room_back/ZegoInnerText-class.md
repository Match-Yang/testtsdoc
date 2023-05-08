

# ZegoInnerText class

<p>控制UI上文案
通过修改对应属性的值达到修改UI上文案的能力。当然你也可以改成其他语言
注意，文案中的<code>%0</code>占位符会被替换成对应的用户名</p>

## Constructors

`ZegoInnerText` ({String? takeSeatMenuButton, String? disagreeButton, String? agreeButton, String? removeSpeakerMenuDialogButton, String? muteSpeakerMenuDialogButton, String? cancelMenuDialogButton, String? memberListTitle, String? memberListRoleYou, String? memberListRoleHost, String? memberListRoleSpeaker, String? removeSpeakerFailedToast, String? messageEmptyToast, String? applyToTakeSeatButton, String? cancelTheTakeSeatApplicationButton, String? memberListAgreeButton, String? memberListDisagreeButton, String? inviteToTakeSeatMenuDialogButton, `ZegoDialogInfo`? cameraPermissionSettingDialogInfo, `ZegoDialogInfo`? microphonePermissionSettingDialogInfo, `ZegoDialogInfo`? removeFromSeatDialogInfo, `ZegoDialogInfo`? leaveSeatDialogInfo, `ZegoDialogInfo`? hostInviteTakeSeatDialog, String? audioEffectTitle, String? audioEffectReverbTitle, String? audioEffectVoiceChangingTitle, String? voiceChangerNoneTitle, String? voiceChangerLittleBoyTitle, String? voiceChangerLittleGirlTitle, String? voiceChangerDeepTitle, String? voiceChangerCrystalClearTitle, String? voiceChangerRobotTitle, String? voiceChangerEtherealTitle, String? voiceChangerFemaleTitle, String? voiceChangerMaleTitle, String? voiceChangerOptimusPrimeTitle, String? voiceChangerCMajorTitle, String? voiceChangerAMajorTitle, String? voiceChangerHarmonicMinorTitle, String? reverbTypeNoneTitle, String? reverbTypeKTVTitle, String? reverbTypeHallTitle, String? reverbTypeConcertTitle, String? reverbTypeRockTitle, String? reverbTypeSmallRoomTitle, String? reverbTypeLargeRoomTitle, String? reverbTypeValleyTitle, String? reverbTypeRecordingStudioTitle, String? reverbTypeBasementTitle, String? reverbTypePopularTitle, String? reverbTypeGramophoneTitle})

## Properties

##### `applyToTakeSeatButton` &#8596; String

观众申请连麦的按钮，默认值为 <code>Apply to take seat</code>  
_<span class="feature">read / write</span>_

##### `audioEffectReverbTitle` &#8596; String

混响分类标题，默认值为 <code>Reverb</code>  
_<span class="feature">read / write</span>_

##### `audioEffectTitle` &#8596; String

音频特效对话框标题，默认值为 <code>Audio effect</code>  
_<span class="feature">read / write</span>_

##### `audioEffectVoiceChangingTitle` &#8596; String

变声分类标题，默认值为 <code>Voice changing</code>  
_<span class="feature">read / write</span>_

##### `cameraPermissionSettingDialogInfo` &#8596; `ZegoDialogInfo`

摄像头权限设置的对话框，默认值为 <code>title: 'Can not use Camera!'</code>， <code>message: 'Please enable camera access in the system settings!'</code>， <code>cancelButtonName: 'Cancel'</code>， <code>confirmButtonName: 'Settings'</code>  
_<span class="feature">read / write</span>_

##### `cancelMenuDialogButton` &#8596; String

弹出式菜单的取消按钮，默认值为 <code>Cancel</code>  
_<span class="feature">read / write</span>_

##### `cancelTheTakeSeatApplicationButton` &#8596; String

观众取消申请连麦的按钮，默认值为  
_<span class="feature">read / write</span>_


##### `hostInviteTakeSeatDialog` &#8596; `ZegoDialogInfo`

主播邀请观众上座后，观众收到的邀请对话框，默认值为 <code>title: 'Invitation'</code>， <code>message: 'The host is inviting you to take seat'</code>， <code>cancelButtonName: 'Disagree'</code>， <code>confirmButtonName: 'Agree'</code>  
_<span class="feature">read / write</span>_

##### `inviteToTakeSeatMenuDialogButton` &#8596; String

主播点击成员列表上更多按钮时出现的邀请观众上座的按钮，默认值 'Invite %0 to take seat'  
_<span class="feature">read / write</span>_

##### `leaveSeatDialogInfo` &#8596; `ZegoDialogInfo`

Speaker主动离开座位前的确认对话框，默认值为 <code>title: 'Leave the seat'</code>， <code>message: 'Are you sure to leave seat?'</code>， <code>cancelButtonName: 'Cancel'</code>， <code>confirmButtonName: 'OK'</code>  
_<span class="feature">read / write</span>_

##### `memberListAgreeButton` &#8596; String

成员列表上接受观众申请上座的按钮，默认值为 <code>Agree</code>  
_<span class="feature">read / write</span>_

##### `memberListDisagreeButton` &#8596; String

成员列表上拒绝观众申请上座的按钮，默认值为 <code>Disagree</code>  
_<span class="feature">read / write</span>_

##### `memberListRoleHost` &#8596; String

成员列表中显示主播的标记，默认值是 <code>Host</code>  
_<span class="feature">read / write</span>_

##### `memberListRoleSpeaker` &#8596; String

成员列表中显示Speaker的标记，默认值是 <code>Speaker</code>  
_<span class="feature">read / write</span>_

##### `memberListRoleYou` &#8596; String

成员列表中显示你自己的标记，默认值是 <code>You</code>  
_<span class="feature">read / write</span>_

##### `memberListTitle` &#8596; String

成员列表标题，默认值为 <code>Audience</code>  
_<span class="feature">read / write</span>_

##### `messageEmptyToast` &#8596; String

聊天输入框没有内容时的提示，默认值为 <code>Say something...</code>  
_<span class="feature">read / write</span>_

##### `microphonePermissionSettingDialogInfo` &#8596; `ZegoDialogInfo`

麦克风权限设置的对话框，默认值为 <code>title: 'Can not use Microphone!'</code>， <code>message: 'Please enable microphone access in the system settings!'</code>， <code>cancelButtonName: 'Cancel'</code>， <code>confirmButtonName: 'Settings'</code>  
_<span class="feature">read / write</span>_

##### `muteSpeakerMenuDialogButton` &#8596; String

Host 点击座位上speaker弹出菜单项的将speaker静音按钮，默认值为 <code>Mute %0</code>  
_<span class="feature">read / write</span>_

##### `removeFromSeatDialogInfo` &#8596; `ZegoDialogInfo`

主播将speaker移下座位前的确认对话框，默认值为 <code>title: 'Remove the speaker'</code>， <code>message: 'Are you sure to remove %0 from the seat?'</code>， <code>cancelButtonName: 'Cancel'</code>， <code>confirmButtonName: 'OK'</code>  
_<span class="feature">read / write</span>_

##### `removeSpeakerFailedToast` &#8596; String

主播尝试将speaker移下座位失败的toast，默认值为 <code>Failed to remove %0 from seat</code>  
_<span class="feature">read / write</span>_

##### `removeSpeakerMenuDialogButton` &#8596; String

Host 点击座位上speaker弹出菜单项的将speaker移下座位按钮，默认值为 <code>Remove %0 from seat</code>  
_<span class="feature">read / write</span>_

##### `reverbTypeBasementTitle` &#8596; String

混响特效：Basement  
_<span class="feature">read / write</span>_

##### `reverbTypeConcertTitle` &#8596; String

混响特效：Concert  
_<span class="feature">read / write</span>_

##### `reverbTypeGramophoneTitle` &#8596; String

混响特效：Gramophone  
_<span class="feature">read / write</span>_

##### `reverbTypeHallTitle` &#8596; String

混响特效：Hall  
_<span class="feature">read / write</span>_

##### `reverbTypeKTVTitle` &#8596; String

混响特效：Karaoke  
_<span class="feature">read / write</span>_

##### `reverbTypeLargeRoomTitle` &#8596; String

混响特效：Large room  
_<span class="feature">read / write</span>_

##### `reverbTypeNoneTitle` &#8596; String

混响特效：None  
_<span class="feature">read / write</span>_

##### `reverbTypePopularTitle` &#8596; String

混响特效：Pop  
_<span class="feature">read / write</span>_

##### `reverbTypeRecordingStudioTitle` &#8596; String

混响特效：Recording studio  
_<span class="feature">read / write</span>_

##### `reverbTypeRockTitle` &#8596; String

混响特效：Rock  
_<span class="feature">read / write</span>_

##### `reverbTypeSmallRoomTitle` &#8596; String

混响特效：Small room  
_<span class="feature">read / write</span>_

##### `reverbTypeValleyTitle` &#8596; String

混响特效：Valley  
_<span class="feature">read / write</span>_


##### `takeSeatMenuButton` &#8596; String

观众点击座位弹出的菜单上的申请上座按钮，默认值为 <code>Take the seat</code>  
_<span class="feature">read / write</span>_

##### `voiceChangerAMajorTitle` &#8596; String

变声特效：A Major  
_<span class="feature">read / write</span>_

##### `voiceChangerCMajorTitle` &#8596; String

变声特效：C Major  
_<span class="feature">read / write</span>_

##### `voiceChangerCrystalClearTitle` &#8596; String

变声特效：Crystal-clear  
_<span class="feature">read / write</span>_

##### `voiceChangerDeepTitle` &#8596; String

变声特效：Deep  
_<span class="feature">read / write</span>_

##### `voiceChangerEtherealTitle` &#8596; String

变声特效：Ethereal  
_<span class="feature">read / write</span>_

##### `voiceChangerFemaleTitle` &#8596; String

变声特效：Female  
_<span class="feature">read / write</span>_

##### `voiceChangerHarmonicMinorTitle` &#8596; String

变声特效：Harmonic minor  
_<span class="feature">read / write</span>_

##### `voiceChangerLittleBoyTitle` &#8596; String

变声特效：Little Boy  
_<span class="feature">read / write</span>_

##### `voiceChangerLittleGirlTitle` &#8596; String

变声特效：LittleGirl  
_<span class="feature">read / write</span>_

##### `voiceChangerMaleTitle` &#8596; String

变声特效：Male  
_<span class="feature">read / write</span>_

##### `voiceChangerNoneTitle` &#8596; String

变声特效：None  
_<span class="feature">read / write</span>_

##### `voiceChangerOptimusPrimeTitle` &#8596; String

变声特效：Optimus Prime  
_<span class="feature">read / write</span>_

##### `voiceChangerRobotTitle` &#8596; String

变声特效：Robot  
_<span class="feature">read / write</span>_
