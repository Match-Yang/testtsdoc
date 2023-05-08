


# ZegoErrorCode class













## Constructors

[ZegoErrorCode](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/ZegoErrorCode.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [AudioEffectPlayerExceedMaxCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/AudioEffectPlayerExceedMaxCount-constant.md) const int



Description: The number of instances of the audio effect player created exceeds the maximum limit. <br>Cause: The number of instances of the audio effect player created exceeds the maximum limit. <br> Solutions: Please check if the number of instances of the audio effect player created exceeds the maximum limit, the maximum number of instances allowed to be created is 1.  




##### [AudioEffectPlayerLoadFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/AudioEffectPlayerLoadFailed-constant.md) const int



Description: Load audio effect resource failed. <br>Cause: Invalid audio effect resource file. <br> Solutions: Check the file format is in the AudioEffectPlayer support file format list or not.  




##### [AudioEffectPlayerNoInstance](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/AudioEffectPlayerNoInstance-constant.md) const int



Description: No audio effect player instance. <br>Cause: The audio effect player instance not created. <br> Solutions: Create an audio effect player instance before using it(createAudioEffectPlayer).  




##### [AudioEffectPlayerPlayFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/AudioEffectPlayerPlayFailed-constant.md) const int



Description: Play audio effect failed. <br>Cause: Invalid audio effect resource file. <br> Solutions: Check the file format is in the AudioEffectPlayer support file format list or not.  




##### [AudioEffectPlayerSeekFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/AudioEffectPlayerSeekFailed-constant.md) const int



Description: Change audio effect progress failed. <br>Cause: The audio effect progress value exceed audio effect file duration. <br> Solutions: Please check the audio effect progress value exceed audio effect file duration or not.  




##### [AudioVADClientInnerNullptr](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/AudioVADClientInnerNullptr-constant.md) const int



Description: SDK internal return null pointer.  




##### [AudioVADClientNoInstance](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/AudioVADClientNoInstance-constant.md) const int



Description: The function call failed. <br>Cause: No audio vad instance has been created. <br>Solutions: Create a audio vad instance.  




##### [CommonAppFlexiableConfigError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonAppFlexiableConfigError-constant.md) const int



Description: The backend configuration of the server is incorrect. <br>Cause: 1. The domain name configuration is incorrect; 2. The media network is abnormal; 3. The media network link is empty. <br>Solutions: Please contact ZEGO technical support.  




##### [CommonAppOfflineError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonAppOfflineError-constant.md) const int



Description: This AppID has been removed from production. <br>Solutions: Please check the status of the AppID on the ZEGO official website console or contact ZEGO technical support.  




##### [CommonCdnAuthParamTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonCdnAuthParamTooLong-constant.md) const int



Description: The Input CDN auth param is too long. <br>Cause: The length of auth parameter passed in when calling <code>enablePublishDirectToCDN</code> or <code>startPlayingStream</code> exceeds the limit. <br>Solutions: Auth param length should be less than 1024 bytes.  




##### [CommonCdnUrlInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonCdnUrlInvalid-constant.md) const int



Description: Incorrect CDN address. <br>Cause: The set CDN URL is not a standard RTMP or FLV protocol. <br>Solutions: Please check the supported protocol and format.  




##### [CommonCdnUrlTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonCdnUrlTooLong-constant.md) const int



Description: The Input CDN URL is too long. <br>Cause: The length of URL parameter passed in when calling <code>enablePublishDirectToCDN</code> or <code>startPlayingStream</code> exceeds the limit. <br>Solutions: URL length should be less than 1024 bytes.  




##### [CommonConfigAfterEngineStarted](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonConfigAfterEngineStarted-constant.md) const int



Description: The engine audio and video module has been activated, and this setting is not supported. <br>Cause: Only supports setting before starting the audio and video module of the engine. <br>Solutions: Please set it before calling <code>startPreviewView</code> <code>startPublishingStream</code> <code>startPlayingStream</code> to start the audio and video module.  




##### [CommonConfigAfterRoomLoggedIn](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonConfigAfterRoomLoggedIn-constant.md) const int



Description: The room is logged in, this setting is not supported. <br>Cause: Only supports setting before logging into the room. <br>Solutions: Please set it before calling <code>loginRoom</code> or after calling <code>logoutRoom</code>. Note that if you log in to multiple rooms, you need to log out of all rooms before setting.  




##### [CommonDispatchError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonDispatchError-constant.md) const int



Server dispatching exception. Please contact ZEGO technical support to solve the problem. This error code is deprecated.  




##### [CommonDnsResolveError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonDnsResolveError-constant.md) const int



DNS resolution failed. Please check network configurations. This error code is deprecated.  




##### [CommonEngineNotCreate](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonEngineNotCreate-constant.md) const int



Description: The engine is not initialized and cannot call non-static functions. <br>Cause: Engine not created.<br>Solutions: Please call the <code>createEngine</code> function to create the engine first, and then call the current function.  




##### [CommonEngineNotStarted](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonEngineNotStarted-constant.md) const int



Description: The audio and video module of the engine is not started and cannot support function realization. <br>Cause: Audio and video modules with no engine started.<br>Solutions: Please call <code>startPreviewView</code> <code>startPublishingStream</code> <code>startPlayingStream</code> to start the audio and video module first.  




##### [CommonEventHandlerExists](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonEventHandlerExists-constant.md) const int



Description: <code>setEventHandler</code> has been called to set the handler, please do not set it repeatedly. <br>Cause: Call <code>setEventHandler</code> repeatedly to set the handler.<br>Solutions: If you need to repeat the settings, please call <code>setEventHandler</code> first to empty the previous handler.  




##### [CommonIllegalParam](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonIllegalParam-constant.md) const int



Illegal param.  




##### [CommonInnerNullptr](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonInnerNullptr-constant.md) const int



Description: SDK internal null pointer error. <br>Cause: The Android JVM environment is abnormal. <br>Solutions: Please check whether the Android JVM environment is normal or contact ZEGO technical support.  




##### [CommonInvalidAndroidEnvironment](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonInvalidAndroidEnvironment-constant.md) const int



Description: Invalid Android context. <br>Cause: Not set or set the wrong Android context environment.<br>Solutions: Set the correct Android context.  




##### [CommonNotLoginRoom](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonNotLoginRoom-constant.md) const int



Description: Not logged in to the room, unable to support function implementation. <br>Cause: Not logged in to the room.<br>Solutions: Please call <code>loginRoom</code> to log in to the room first, and use related functions during the online period after entering the room.  




##### [CommonSdkNoModule](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonSdkNoModule-constant.md) const int



Description: The current SDK does not support this feature. <br>Cause: The SDK version used does not include this feature.<br>Solutions: Please contact ZEGO technical support.  




##### [CommonStreamIdInvalidCharacter](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonStreamIdInvalidCharacter-constant.md) const int



Description: The input streamID contains invalid characters. <br>Cause: The streamID parameter passed in when calling <code>startPublishingStream</code> or <code>startPlayingStream</code> contains invalid characters. <br>Solutions: Check whether the streamID parameter passed in when calling the function is normal, only support numbers, English characters and '-', '_'.  




##### [CommonStreamIdNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonStreamIdNull-constant.md) const int



Description: The input StreamID is null. <br>Cause: The streamID parameter passed in when calling <code>startPublishingStream</code> or <code>startPlayingStream</code> is null or empty string. <br>Solutions: Check whether the streamID parameter passed in when calling the function is normal.  




##### [CommonStreamIdTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonStreamIdTooLong-constant.md) const int



Description: The input streamID is too long. <br>Cause: The length of the streamID parameter passed in when calling <code>startPublishingStream</code> or <code>startPlayingStream</code> exceeds the limit. <br>Solutions: The streamID should be less than 256 bytes.  




##### [CommonSuccess](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonSuccess-constant.md) const int



Execution successful.  




##### [CommonUnsupportedPlatform](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonUnsupportedPlatform-constant.md) const int



Description: Call functions that are not supported on the current system/platform. <br>Cause: For example, calling the function of setting the Android context environment on a non-Android system.<br>Solutions: Check if the system environment matches.  




##### [CommonUserNotSame](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CommonUserNotSame-constant.md) const int



Description: When login room or login scene, userID or user name is different. <br>Cause: Login room, login scene use different user id or user name. <br> Solutions: Use same user id and user name when login room, login scene.  




##### [CopyrightedMusicAppidInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicAppidInvalid-constant.md) const int



Description: AppID invalid. <br>Cause: The appID is not support copyrighted music. <br>Solutions: Please contact ZEGO technical support.  




##### [CopyrightedMusicBillingModeInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicBillingModeInvalid-constant.md) const int



Description: Billing mode invalid. <br>Cause: Billing mode invalid. <br>Solutions: Please select correct billing mode.  




##### [CopyrightedMusicCommandInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicCommandInvalid-constant.md) const int



Description: The command invalid. <br>Cause: The command entered by the <code>sendExtendedRequest</code> function is empty. <br>Solutions: Please check the command entered when calling the <code>sendExtendedRequest</code> function to make sure it is not empty.  




##### [CopyrightedMusicCopyrightedMusicAuthParamInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicCopyrightedMusicAuthParamInvalid-constant.md) const int



Description: Copyright music init authentication failed. <br>Cause: Appsign or token is not set. <br>Solutions: When using token authentication, call <code>loginRoom</code> before calling <code>initCopyrightedMusic</code> or use appsign authentication.  




##### [CopyrightedMusicCopyrightedServerFail](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicCopyrightedServerFail-constant.md) const int



Description: Request copyrighted server fail. <br>Cause: The params entered make mistake or some network reasons. <br>Solutions: Please check the params entered and retry.  




##### [CopyrightedMusicDownloading](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicDownloading-constant.md) const int



Description: Downloading. <br>Cause: Download same resource. <br>Solutions: Please wait for the resource to download successfully.  




##### [CopyrightedMusicFreeSpaceLimit](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicFreeSpaceLimit-constant.md) const int



Description: Free space limit. <br>Cause: Free space limit. <br>Solutions: Please clean up local files and make sure there is enough free disk space.  




##### [CopyrightedMusicGetLyricFail](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicGetLyricFail-constant.md) const int



Description: Get lyric fail. <br>Cause: Lyrics not found. <br>Solutions: Please try again later.  




##### [CopyrightedMusicGetPitchFail](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicGetPitchFail-constant.md) const int



Description: Get pitch fail. <br>Cause: Pitch not found. <br>Solutions: Please try again later.  




##### [CopyrightedMusicGetSharedResourceTimesOver](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicGetSharedResourceTimesOver-constant.md) const int



Description: The number of times the resource is free in the room is exhausted. <br>Cause: 1. The shared resources cannot be obtained again; 2. Shared resources have been obtained. <br>Solutions: Please use the acquired resources, or use <code>requestResource</code> to share resources again  




##### [CopyrightedMusicIllegalParam](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicIllegalParam-constant.md) const int



Description: Illegal param. <br>Cause: The entered param is incorrect. <br>Solutions: Please check param when entered function to make sure it is correct.  




##### [CopyrightedMusicInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicInnerError-constant.md) const int



Description: Failed due to internal system exceptions.<br>Cause: Unknown internal error.<br>Solutions: Contact ZEGO technical support to deal with it.  




##### [CopyrightedMusicKrcTokenExpired](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicKrcTokenExpired-constant.md) const int



Description: krcToken expired. <br>Cause: krcToken expired. <br>Solutions: Please select an unexpired krcToken to get lyrics in KRC format.  




##### [CopyrightedMusicKrcTokenIllegal](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicKrcTokenIllegal-constant.md) const int



Description: krcToken illegal. <br>Cause: krcToken illegal. <br>Solutions: Please check krcToken when entered by calling <code>getKrcLyricByKrcToken</code> to make sure it is correct.  




##### [CopyrightedMusicKrcTokenInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicKrcTokenInvalid-constant.md) const int



Description: The krcToken invalid. <br>Cause: The krcToken entered is empty. <br>Solutions: Please check the krcToken entered when calling the function to make sure it is not empty.krcToken can be obtained by call <code>requestAccompaniment</code>  




##### [CopyrightedMusicNetworkError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicNetworkError-constant.md) const int



Description: Failed due to network exceptions.<br>Cause: Unknown internal error.<br>Solutions: Contact ZEGO technical support to deal with it.  




##### [CopyrightedMusicNoAccompany](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicNoAccompany-constant.md) const int



Description: No accompany. <br>Cause: Music don't have accompany. <br>Solutions: Please choice music have accompany.  




##### [CopyrightedMusicNoCopyright](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicNoCopyright-constant.md) const int



Description: No copyright, unable to listen to and sing songs. <br>Cause: No copyright. <br>Solutions: Please select another music.  




##### [CopyrightedMusicNoInit](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicNoInit-constant.md) const int



Description: The copyright music module is not initialized. <br>Cause: The <code>initCopyrightedMusic</code> method is not called to initialize the copyright module. <br>Solutions: Please call the <code>initCopyrightedMusic</code> method first.  




##### [CopyrightedMusicNonMonthlyMembership](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicNonMonthlyMembership-constant.md) const int



Description: Non monthly membership. <br>Cause: Unopened monthly membership. <br>Solutions: Open monthly membership or ues COUNT mode request music.  




##### [CopyrightedMusicNoPermissionsOfLyricsAndMusic](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicNoPermissionsOfLyricsAndMusic-constant.md) const int



Description: No permissions of accompaniment, can only listen to songs, not sing. <br>Cause: No permissions of accompaniment. <br>Solutions: Please select another music.  




##### [CopyrightedMusicNotSharedResource](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicNotSharedResource-constant.md) const int



Description: This resource is not shared in the room. <br>Cause: No users in the room share this resource. <br>Solutions: Please any one user in the room to call the <code>requestresource</code> function to request resources and share them.  




##### [CopyrightedMusicNotSupportMethod](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicNotSupportMethod-constant.md) const int



Description: The copyright music module does not support this method. <br>Cause: The copyright music module does not support this function under the current platform. <br>Solutions: Contact ZEGO technical support to deal with it.  




##### [CopyrightedMusicParamsInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicParamsInvalid-constant.md) const int



Description: The params invalid. <br>Cause: The params entered by the <code>sendExtendedRequest</code> function is empty. <br>Solutions: Please check the params entered when calling the <code>sendExtendedRequest</code> function to make sure it is not empty.  




##### [CopyrightedMusicPositionInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicPositionInvalid-constant.md) const int



Description: The position invalid. <br>Cause: The position entered by the fuction <code>seek</code> is invalid. <br>Solutions: Please check the position entered when calling the function <code>seek</code> to make sure it is in 0 ~ song duration.  




##### [CopyrightedMusicResourceFileExpired](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicResourceFileExpired-constant.md) const int



Description: Resource file expired. <br>Cause: The resource file has expired. <br>Solutions: Please request song or accompaniment again.  




##### [CopyrightedMusicResourceFileInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicResourceFileInvalid-constant.md) const int



Description: Resource file invalid. <br>Cause: File is corrupted <br>Solutions: Please call <code>download</code> function to reload media resource.  




##### [CopyrightedMusicResourceFileNotExist](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicResourceFileNotExist-constant.md) const int



Description: Resource file not exist. <br>Cause: Resource file has been deleted. <br>Solutions: Please reload resource.  




##### [CopyrightedMusicResourceIdInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicResourceIdInvalid-constant.md) const int



Description: The resource_id invalid. <br>Cause: The resource_id entered is empty. <br>Solutions: Please check the resource_id entered when calling the function to make sure it is not empty.resource_id can be obtained by call <code>requestSong</code> <code>requestAccompaniment</code> <code>getMusicByToken</code>  




##### [CopyrightedMusicResourceIdUnauthorized](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicResourceIdUnauthorized-constant.md) const int



Description: The resource_id unauthorized. <br>Cause: When <code>download</code> is called to download resources, the resource_id is unauthorization. <br>Solutions: Please call the <code>requestSong</code> <code>requestAccompaniment</code> <code>requestAccompanimentClip</code> <code>getMusicByToken</code> function before call <code>load</code> function to load resource.  




##### [CopyrightedMusicResourceNotExist](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicResourceNotExist-constant.md) const int



Description: Resource not exist. <br>Cause: Resource not exist. <br>Solutions: Please select another music.  




##### [CopyrightedMusicShareTokenExpired](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicShareTokenExpired-constant.md) const int



Description: Share token expired. <br>Cause: Share token expired. <br>Solutions: Please select an unexpired sharing token to get resources.  




##### [CopyrightedMusicShareTokenIllegal](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicShareTokenIllegal-constant.md) const int



Description: Share token illegal. <br>Cause: Share token illegal. <br>Solutions: Please check songToken when entered by calling <code>getMusicByToken</code> to make sure it is correct.  




##### [CopyrightedMusicShareTokenInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicShareTokenInvalid-constant.md) const int



Description: The share_token invalid. <br>Cause: The share_token entered is empty. <br>Solutions: Please check the share_token entered when calling the function to make sure it is not empty.share_token can be obtained by call <code>requestAccompaniment</code>  




##### [CopyrightedMusicSongIdInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicSongIdInvalid-constant.md) const int



Description: The song_id invalid. <br>Cause: The song_id entered is empty. <br>Solutions: Please check the song_id entered when calling the function to make sure it is not empty.  




##### [CopyrightedMusicStartPositionInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicStartPositionInvalid-constant.md) const int



Description: The start_position invalid. <br>Cause: The start_position entered by the fuction <code>loadCopyrightedMusicResourceWithPosition</code> is invalid. <br>Solutions: Please check the start_position entered when calling the function <code>loadCopyrightedMusicResourceWithPosition</code> to make sure it is in 0 ~ song duration.  




##### [CopyrightedMusicSystemBusy](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicSystemBusy-constant.md) const int



Description: System is busy. <br>Cause: System is busy. <br>Solutions: Please try again.  




##### [CopyrightedMusicUnreasonableAccess](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicUnreasonableAccess-constant.md) const int



Description: Unreasonable_access. <br>Cause: Monthly membership request music by COUNT. <br>Solutions: Please select correct billing mode.  




##### [CopyrightedMusicVolumeInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CopyrightedMusicVolumeInvalid-constant.md) const int



Description: The volume invalid.. <br>Cause: The Volume entered by the fuction <code>setPlayVolume</code> is invalid. <br>Solutions: Please check the Volume entered when calling the function <code>setPlayVolume</code> to make sure it is in 0 ~ 200.  




##### [CustomAudioIOAudioDataCallbackSampleRateNoSupport](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomAudioIOAudioDataCallbackSampleRateNoSupport-constant.md) const int



Description: The sample rate parameter is illegal. <br>Cause: Capture and render mix results recording does not support 8000, 22050, 24000 sample rates. <br> Solutions: Please confirm whether the sample rate parameter value allowed by the interface is legal.  




##### [CustomAudioIOCapturerNotCreated](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomAudioIOCapturerNotCreated-constant.md) const int



Description: The custom audio capture feature is not enabled. <br>Cause: The custom audio capture feature is not enabled. <br> Solutions: Please make sure that the custom audio IO module is enabled for the specified stream publishing channel.  




##### [CustomAudioIOEnableCustomAudioIoFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomAudioIOEnableCustomAudioIoFailed-constant.md) const int



Description: Failed to enable/disable custom audio IO. <br>Cause: Failed to enable/disable custom audio IO. <br> Solutions: Please make sure to enable/disable it before the engine is started (i.e., before calling <code>startPreview</code>, <code>startPublishingStream</code> or <code>startPlayingStream</code>).  




##### [CustomAudioIORendererNotCreated](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomAudioIORendererNotCreated-constant.md) const int



Description: The custom audio rendering feature is not enabled. <br>Cause: The custom audio rendering feature is not enabled. <br> Solutions: Please make sure that the custom audio IO module is enabled.  




##### [CustomAudioIOUnsupportedAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomAudioIOUnsupportedAudioSourceType-constant.md) const int



Description: Unsupported custom audio source type. <br>Cause: Only channel_aux supports zego_audio_source_type_media_player. <br> Solutions: Select the correct custom audio source type.  




##### [CustomVideoIOCapturerNotCreated](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomVideoIOCapturerNotCreated-constant.md) const int



Description: The custom video capturer is not created. <br>Cause: Create custom video capturer before onStart callback received. <br> Solutions: Please create custom video capturer after received onStart callback.  




##### [CustomVideoIOEnableCustomIoFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomVideoIOEnableCustomIoFailed-constant.md) const int



Description: Failed to enable/disable custom video capture/rendering. <br>Cause: Not enable/disable custom video capture/rendering before engine is started. <br> Solutions: Please make sure to enable/disable custom video capture/rendering before engine is started, i.e., before calling (startPreview), (startPublishingStream), (startPlayingStream), (createMediaPlayer) or (createAudioEffectPlayer).  




##### [CustomVideoIONoCustomVideoCapture](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomVideoIONoCustomVideoCapture-constant.md) const int



Description: The custom video capture module is not enabled. <br>Cause: Custom video capture module is not enabled in initialization configurations. <br> Solutions: Please contact ZEGO technical support, make sure custom video capture module is enabled in initialization configurations.  




##### [CustomVideoIONoCustomVideoProcessing](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomVideoIONoCustomVideoProcessing-constant.md) const int



Description: The custom video process module is not enabled. <br>Cause: The custom video process module is not enabled. <br> Solutions: Call <code>enableCustomVideoProcessing</code> to enable a custom video capturermodule.  




##### [CustomVideoIONotSupportedBufferType](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomVideoIONotSupportedBufferType-constant.md) const int



Description: Custom video rendering does not support the currently set video buffer type. <br>Cause: The buffer_type in the config parameter of <code>enableCustomVideoRender</code> only supports raw_data, cv_pixel_buffer, encoded_data. For <code>enableCustomVideoProcessing</code>, only raw_data is supported on Windows platform, only cv_pixel_buffer is supported on Apple devices, and gl_texture_2d and surface_texture are supported on Android platform. <br> Solutions: Select the correct video buffer type.  




##### [CustomVideoIONotSupportedFormat](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomVideoIONotSupportedFormat-constant.md) const int



Description: The currently configured custom video capture format does not support this API. <br>Cause: The currently configured custom video capture format does not support this API. <br> Solutions: Please contact ZEGO technical support.  




##### [CustomVideoIOProcessModuleNotCreated](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/CustomVideoIOProcessModuleNotCreated-constant.md) const int



Description: The custom video capturer is not created. <br>Cause: Internal video-related modules are not created. <br> Solutions: Please call <code>startPreview</code> or <code>startPublishingStream</code> first.  




##### [DeviceAudioSpectrumIntervalInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceAudioSpectrumIntervalInvalid-constant.md) const int



Description: The set audio spectrum monitoring interval is out of range.<br>Cause:  The set audio spectrum monitoring interval is less than 10 milliseconds.<br>Solutions: Reset audio spectrum monitoring interval which is not less than 10 milliseconds.  




##### [DeviceAudioVadStableStateMonitorTypeInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceAudioVadStableStateMonitorTypeInvalid-constant.md) const int



invalid audio VAD monitor type  




##### [DeviceErrorMediaServicesLost](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceErrorMediaServicesLost-constant.md) const int



Description: The device media is lost.<br>Cause: Media service cannot be restored.<br>Solutions: Restart device.  




##### [DeviceErrorTypeGeneric](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceErrorTypeGeneric-constant.md) const int



Description: Generic device error.<br>Cause: Device dose not work normally.<br>Solutions: Use the system's video or audio recording application to check whether the device can work normally. If the device is normal, please contact ZEGO technical support.  




##### [DeviceErrorTypeInUseByOther](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceErrorTypeInUseByOther-constant.md) const int



Description: The device is occupied.<br>Cause: The device is occupied by other programs.<br>Solutions: Please use the system's video or audio recording application to check whether the device is working properly and make sure that the device is not occupied by other applications.  




##### [DeviceErrorTypeInvalidId](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceErrorTypeInvalidId-constant.md) const int



Description: The device ID does not exist.<br>Cause: The device ID is spelled incorrectly, or the corresponding device is unplugged.<br>Solutions: Please use the SDK interface to obtain the device ID, and check whether the device is properly connected.  




##### [DeviceErrorTypeNoAuthorization](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceErrorTypeNoAuthorization-constant.md) const int



Description: No permission to access the device. <br>Cause: Did not apply for or obtain the permission to use the corresponding device.<br>Solutions: Please check whether the application has correctly applied for the camera or microphone permission, and whether the user has granted the corresponding permission.  




##### [DeviceErrorTypeRebootRequired](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceErrorTypeRebootRequired-constant.md) const int



Description: The device needs to be restarted.<br>Cause: Device driver update, or device error requires restart.<br>Solutions: Restart device.  




##### [DeviceErrorTypeUnplugged](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceErrorTypeUnplugged-constant.md) const int



Description: The device is unplugged.<br>Cause: The device is unplugged or not properly connected.<br>Solutions: Check the device wiring and reconnect the device.  




##### [DeviceErrorTypeZeroFps](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceErrorTypeZeroFps-constant.md) const int



Description: The frame rate of the capture device is 0.<br>Cause: Device error, or device does not have permission.<br>Solutions: Please use the system's video or audio recording application to check whether the device can work normally. Please check whether the application has correctly applied for the camera or microphone permission, and whether the user has granted the corresponding permission. If the device is normal and the application has obtained the corresponding device permissions, please contact ZEGO technical support.  




##### [DeviceExposureCompensationValueInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceExposureCompensationValueInvalid-constant.md) const int



Description: Failed to set the camera exposure compensation. <br>Cause: The set camera exposure compensation value is out of range. <br>Solutions: Set the camera exposure compensation range between <code>-1,1</code>.  




##### [DeviceFreeDeviceListNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceFreeDeviceListNull-constant.md) const int



Description: The device list cannot be empty when trying to release devices.<br>Cause: The device list has been released or has not been initialized.<br>Solutions: Ignore it.  




##### [DeviceInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceInnerError-constant.md) const int



Description: Internal error of the device. <br>Solutions: Contact ZEGO technical support.  




##### [DeviceSouldLevelIntervalInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceSouldLevelIntervalInvalid-constant.md) const int



Description: The set sound level monitoring interval is out of range.<br>Cause: The set sound level monitoring interval is less than 100 milliseconds, or greater than 3000 milliseconds.<br>Solutions: Reset the effective sound level monitoring interval, the effective sound level monitoring interval is <code>100, 3000</code>, in milliseconds.  




##### [DeviceZoomFactorInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/DeviceZoomFactorInvalid-constant.md) const int



Description: Failed to set the camera zoom. <br>Cause: The set camera zoom factor is out of range. <br>Solutions: The set camera zoom factor cannot exceed the maximum range obtained, the maximum range can be obtained through <code>getCameraMaxZoomFactor</code>.  




##### [EngineAppidIncorrectOrNotOnline](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineAppidIncorrectOrNotOnline-constant.md) const int



Description: Authentication failed. <br>Cause: Incorrect AppID; using AppID in wrong environment. <br>Solutions: Please check AppID is correct or not on ZEGO manage console, or check whether the environment configured by AppID is consistent with the environment set by SDK.  




##### [EngineAppidZero](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineAppidZero-constant.md) const int



AppID cannot be 0. Please check if the AppID is correct.  




##### [EngineAppsignIncorrect](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineAppsignIncorrect-constant.md) const int



Description: Authentication failed. <br>Cause: Incorrect AppSign. <br>Solutions: Please check AppSign is correct or not on ZEGO manage console.  




##### [EngineAppsignInvalidCharacter](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineAppsignInvalidCharacter-constant.md) const int



The input AppSign contains invalid characters. Only '0'-'9', 'a'-'f', 'A'-'F' are valid.  




##### [EngineAppsignInvalidLength](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineAppsignInvalidLength-constant.md) const int



The length of the input AppSign must be 64 bytes.  




##### [EngineAppsignNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineAppsignNull-constant.md) const int



The input AppSign is empty.  




##### [EngineExperimentalJsonStrInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineExperimentalJsonStrInvalid-constant.md) const int



Description: The experimental API json parameter parsing failed. <br>Cause: Invalid json format; wrong function name or parameter. <br>Solutions: Please check json format is valid or not; check function name or parameter is correct or not, contact ZEGO technical support for specific function name and parameters.  




##### [EngineLogNoWritePermission](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineLogNoWritePermission-constant.md) const int



Description: No write permission to the log file. <br>Cause: App has no write permission to log file folder. <br>Solutions: Please check has grant write permission to App or not; check log folder is protected or not.  




##### [EngineLogPathTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineLogPathTooLong-constant.md) const int



Description: The log file path is too long. <br>Cause: The length of log file path exceeds limit. <br>Solutions: Please check the length of log file path.  




##### [EngineSetRoomModeErrorTime](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/EngineSetRoomModeErrorTime-constant.md) const int



Description: Set room mode failed. <br>Cause: Set room mode after initialize the SDK. <br>Solutions: Please set room mode before initialize the SDK.  




##### [IMBroadcastMessageQpsOverload](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMBroadcastMessageQpsOverload-constant.md) const int



Description: Failed to send broadcast message,. <br>Cause: QPS exceeds the limit. <br>Solutions: Control the maximum QPS is 2 .  




##### [IMContentNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMContentNull-constant.md) const int



Description: the input message content is empty <br>Cause: imessage content is empty <br>Solutions: Input a non-empty message.  




##### [IMContentTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMContentTooLong-constant.md) const int



Description: The input message content is too long <br>Cause: message more than 1024 bytes. <br>Solutions: The maximum length should be less than 1024 byte  




##### [IMDataTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMDataTooLong-constant.md) const int



Description: The input real-time sequential data is too long. <br>Cause: The length of the input data is greater than 4096 bytes. <br>Solution: Check the length of the input data, consider splitting the large data packet into multiple small data and sending it multiple times.  




##### [IMInconsistentRoomId](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMInconsistentRoomId-constant.md) const int



Description: The room where the message is sent is different from the room currently logged in. <br>Cause: The room where the message is sent is different from the room currently logged in. <br>Solutions: Send a message to the current logged-in room ID.  




##### [IMInputParamsLengthLimit](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMInputParamsLengthLimit-constant.md) const int



Description: Failed to send message. <br>Cause: The message input length exceeds the limit. <br>Solutions: Check the input content length or contact ZEGO technical support to expand the message content length.  




##### [IMManagerCreationFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMManagerCreationFailed-constant.md) const int



Description: The real-time sequential data manager instance creation failed. <br>Cause: A manager instance with this room ID has already been created. <br>Solution: A maximum of 1 instance can be created for each room ID. If you need to create multiple instances, please use other room IDs.  




##### [IMNoAvailableBroadcastChannel](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMNoAvailableBroadcastChannel-constant.md) const int



Description: No publish channel available for broadcasting. <br>Cause: The developer has used all publish channels. <br>Solution: Do not use all the publish channels, check if there are any streams that can stop publsihing, or contact ZEGO technical support to increase the available publish channels.  




##### [IMNoAvailableStreamId](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMNoAvailableStreamId-constant.md) const int



Description: The stream ID to start broadcasting is not available. <br>Cause: The stream ID has been used in this device for RTC business (e.g. <code>startPublishingStream</code> / <code>startPlayingStream</code>). <br>Solution: Please use another stream ID for broadcasting.  




##### [IMNoBroadcatingStream](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMNoBroadcatingStream-constant.md) const int



Description: The stream to stop broadcasting does not exist. <br>Cause: The stream ID set <code>stopBroadcasting</code> function is not in broadcasting. <br>Solution: Check if the stream ID is correct, or if the stream ID is not in broadcasting.  




##### [IMNoManagerInstance](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMNoManagerInstance-constant.md) const int



Description: The specified real-time sequential data manager instance could not be found. <br>Cause: This manager instance has not been created yet. <br>Solution: Please call the <code>createRealTimeSequentialDataManager</code> function to create a manager instance first.  




##### [IMNoSubscribingStream](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMNoSubscribingStream-constant.md) const int



Description: The stream to stop subscribing does not exist. <br>Cause: The stream ID set <code>stopSubscribing</code> function is not in subscribing. <br>Solution: Check if the stream ID is correct, or if the stream ID is not in subscribing.  




##### [IMRealTimeSequentialDataSendFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMRealTimeSequentialDataSendFailed-constant.md) const int



Description: Failed to send real-time sequential data. <br>Cause: The broadcast has not started yet, or the broadcast has encountered network problems. <br>Solution: Check whether <code>startBroadcasting</code> has been called to start broadcasting, or check whether the network is normal.  




##### [IMRepeatBroadcast](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMRepeatBroadcast-constant.md) const int



Description: Repeat broadcast. <br>Cause: The developer repeatedly calls the <code>startBroadcasting</code> function. <br>Solution: Please check the business logic to avoid repeating the broadcast for the stream which is broadcasting.  




##### [IMRepeatSubscribe](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMRepeatSubscribe-constant.md) const int



Description: Repeat broadcast. <br>Cause: The developer repeatedly calls the <code>startBroadcasting</code> function. <br>Solution: Please check the business logic to avoid repeating the subscribe for the stream which is subscribing.  




##### [IMSendFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMSendFailed-constant.md) const int



Description: Failed to send the message. <br>Cause: network problems. <br>Solutions: Check the network.  




##### [IMUserIdEmpty](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMUserIdEmpty-constant.md) const int



Description: Failed to send custom command. <br>Cause: The entered user ID is empty. <br>Solutions: Please enter the correct user ID.  




##### [IMUserIdTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/IMUserIdTooLong-constant.md) const int



Description: Failed to send custom signaling. <br>Cause: The entered user ID is too long. <br>Solutions: Please enter the correct user ID, the maximum user ID cannot exceed 64 bytes.  




##### [MediaDataPublisherExceedMaxCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaDataPublisherExceedMaxCount-constant.md) const int



Description: The number of instances of the media data publisher created exceeds the maximum limit. <br>Cause: The number of instances of the media data publisher created exceeds the maximum limit. <br> Solutions: Please check if the number of instances of the media data publisher created exceeds the maximum limit, the maximum number of instances allowed to be created is 1.  




##### [MediaDataPublisherFileCodecError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaDataPublisherFileCodecError-constant.md) const int



Description: File decoding exception. <br>Cause: Invalid media file format. <br>Solutions: Please check the file is a valid media file or not; check the file format is in the MediaPlayer support file format list or not.  




##### [MediaDataPublisherFileParseError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaDataPublisherFileParseError-constant.md) const int



Description: This error code is deprecated. <br>Cause: None. <br> Solutions: None.  




##### [MediaDataPublisherFilePathError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaDataPublisherFilePathError-constant.md) const int



Description: This error code is deprecated. <br>Cause: None. <br> Solutions: None.  




##### [MediaDataPublisherNoInstance](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaDataPublisherNoInstance-constant.md) const int



Description: The MediaDataPublisher instance is not created. <br>Cause: The MediaDataPublisher instance is not created. <br> Solutions: Call <code>createMediaDataPublisher</code> to create a media pusher instance.  




##### [MediaDataPublisherTimestampGoBackError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaDataPublisherTimestampGoBackError-constant.md) const int



Description: Timestamp error. <br>Cause: the later frame timestamp is smaller than the previous frame timestamp. <br>Solutions: Please provide the media file, and contact ZEGO technical support.  




##### [MediaPlayerDemuxError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerDemuxError-constant.md) const int



Description: The MediaPlayer failed to load the file. <br>Cause: There was an error during file resolution. <br> Solutions: Try again or contact ZEGO technical support.  




##### [MediaPlayerExceedMaxCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerExceedMaxCount-constant.md) const int



Description: The number of MediaPlayer instances exceeds the maximum number allowed. <br>Cause: The number of MediaPlayer instances exceeds the maximum number allowed. Up to 4 instances can be created. <br> Solutions: Media players can create up to 4 instances, and make sure that the number of media player instances is not exceeded the maximum limit.  




##### [MediaPlayerFileDecodeError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerFileDecodeError-constant.md) const int



Description: The MediaPlayer failed to load the file. <br>Cause: The file decoding failed. <br> Solutions: Check that the media file is corrupted or contact ZEGO technical support.  




##### [MediaPlayerFileExpired](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerFileExpired-constant.md) const int



Description: The copyrighted music resource file has expired. <br>Cause: The resource file has expired. <br>Solutions: Please request song or accompaniment again.  




##### [MediaPlayerFileFormatError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerFileFormatError-constant.md) const int



Description: The MediaPlayer failed to load the file. <br>Cause: File formats are not supported. <br> Solutions: Files in this format are not supported, please use files in the supporting format.  




##### [MediaPlayerFileNoSupportedStream](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerFileNoSupportedStream-constant.md) const int



Description: The MediaPlayer failed to load the file. <br>Cause: No supported audio/video stream exists. <br> Solutions: Check that the media file data is empty.  




##### [MediaPlayerFilePathNotExists](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerFilePathNotExists-constant.md) const int



Description: The MediaPlayer failed to load the file. <br>Cause: The file path does not exist. <br> Solutions: Check the validity of the media file path.  




##### [MediaPlayerInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerInnerError-constant.md) const int



Description: MediaPlayer internal error. <br>Cause: internal error. <br>Solutions: Contact Technical support.  




##### [MediaPlayerNoFilePath](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerNoFilePath-constant.md) const int



Description: The MediaPlayer failed to play the media. <br>Cause: The resource file is not loaded. <br> Solutions: The media player loads the media resource <code>loadResource</code> before starting.  




##### [MediaPlayerNoInstance](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerNoInstance-constant.md) const int



Description: The MediaPlayer failed to play the media. <br>Cause: The resource file is not loaded. <br> Solutions: Create a media player instance before using media players <code>createMediaPlayer</code>.  




##### [MediaPlayerParamValueRangeIllegal](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerParamValueRangeIllegal-constant.md) const int



Description: the passed parameter is not in the valid value range. <br>Cause: error setting parameters. <br>Solutions: Review the interface comment and pass in a value within the legal range.  




##### [MediaPlayerPlatformFormatNotSupported](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerPlatformFormatNotSupported-constant.md) const int



Description: The MediaPlayer is configured with a video data format not supported by the platform. <br>Cause: The MediaPlayer is configured with a video data format not supported by the platform (e.g., CVPixelBuffer on iOS does not support NV21). <br> Solutions: Check the data format <code>setVideoHandler</code> supported by the current media player platform and set the correct data format.  




##### [MediaPlayerSeekError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerSeekError-constant.md) const int



Description: The MediaPlayer failed to seek. <br>Cause: The file hasn't been loaded yet. <br> Solutions: The media player loads the media resource <code>loadResource</code> before seeking <code>seekTo</code>.  




##### [MediaPlayerSetAudioTrackIndexError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerSetAudioTrackIndexError-constant.md) const int



Description: The media player failed to specify the audio track index. <br>Cause: The audio track index not exist. <br>Solutions: Check file audio track index call <code>getAudioTrackCount</code> can get.  




##### [MediaPlayerSetVoiceChangerParamInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerSetVoiceChangerParamInvalid-constant.md) const int



Description: Media player setting sound change parameter invalid. <br>Cause: Error setting parameters. <br>Solutions: Checking setting parameters control during -12.0 to 12.0  




##### [MediaPlayerTakeSnapshotTimingError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MediaPlayerTakeSnapshotTimingError-constant.md) const int



Description: takeSnapshot screenshot failed <br>Cause: The video is not playing or 'setPlayerCanvas' is not called to display the video to the control. <br>Solutions: Check whether the video plays normally(check <code>onPlayStart</code> callback) and the screen is displayed normally.  




##### [MixerAdvancedConfigTooLongError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerAdvancedConfigTooLongError-constant.md) const int



Description: The mixed-flow advanced configuration is too long. <br>Cause: The length of the mixed stream advanced configuration parameter exceeds the limit. <br>Solutions: Please make sure that the advanced configuration length does not exceed 512 bytes.  




##### [MixerAudioConfigInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerAudioConfigInvalid-constant.md) const int



Description: The video configuration of the stream mixing task is invalid. <br>Cause: 1. An unsupported audio codec format is used. 2. The audio bit rate exceeds 192 kbps. <br>Solutions: Please check the audio configuration of the stream mixing task.  




##### [MixerAuthenticationFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerAuthenticationFailed-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: Mixed-stream authentication failed. <br>Solutions: Contact ZEGO technical support.  




##### [MixerAutoMixStreamServerNotFound](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerAutoMixStreamServerNotFound-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The auto-mixing server was not found. <br>Solutions: Please contact ZEGO technical support.  




##### [MixerBackgroundImageUrlInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerBackgroundImageUrlInvalid-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The URL of the background image entered is illegal. <br>Solutions: The URL of the background image must start with preset-id:// and end with <code>.jpg</code> or <code>.png</code>.  




##### [MixerExceedMaxAudioFocusStreamCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerExceedMaxAudioFocusStreamCount-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The maximum number of focus voice input streams is exceeded. <br>Solutions: Support up to 4 input streams to set the focus voice.  




##### [MixerExceedMaxInputCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerExceedMaxInputCount-constant.md) const int



Description: The number of input streams exceeds the maximum number allowed. <br>Cause: Supports up to 9 input streams, and may pass more than 9 input streams. <br>Solutions: Please check the input stream configuration of the mixing task.  




##### [MixerExceedMaxOutputCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerExceedMaxOutputCount-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: Exceeding the maximum number of output streams. <br>Solutions: Support up to 3 output streams.  




##### [MixerInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerInnerError-constant.md) const int



Description: Stream mixing internal error.<br>Cause: Unknown error occured in stream mixing internal.<br>Solutions: Please contact ZEGO technical support.  




##### [MixerInputImageUrlFormatError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerInputImageUrlFormatError-constant.md) const int



Description: Failed to mix stream input image. <br>Cause: The image format of the mixed stream input parameter is incorrect. <br>Solution: Use JPG and PNG formats. There are 2 ways to use it: 1. URI: Provide the picture to ZEGO technical support for configuration. After the configuration is complete, the picture URI will be provided, for example: preset-id://xxx.jpg. 2. URL: Only HTTP protocol is supported.  




##### [MixerInputImageUrlSizeError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerInputImageUrlSizeError-constant.md) const int



Description: Failed to mux input image. <br>Cause: The image size of the mixed stream input parameter exceeds the limit. <br>Solution: Image size is limited to 1M.  




##### [MixerInputImageUrlTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerInputImageUrlTooLong-constant.md) const int



Description: The link to the muxed input image is too long. <br>Cause: The length of the image link of the mixed stream input parameter exceeds the limit. <br>Solution: Please make sure that the length of the input image link does not exceed 1024 bytes.  




##### [MixerInputLabelTextTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerInputLabelTextTooLong-constant.md) const int



Description: Mixed input text watermark is too long. <br>Cause: The length of the text watermark of the mixed stream input parameter exceeds the limit. <br>Solutions: Please make sure the input text watermark length does not exceed 512 bytes.  




##### [MixerInputListInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerInputListInvalid-constant.md) const int



Description: The input stream list of the stream mixing task is empty. <br>Cause:  The input stream list of the stream mixing task is empty. <br>Solutions: Please check the input stream list of the mixing task.  




##### [MixerInputParametersError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerInputParametersError-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The mixed stream input parameter is wrong, it may be that the layout of the input stream exceeds the canvas range. <br>Solutions: Please enter the correct mixed stream parameters. <a href="../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md">ZegoMixerTask</a>  




##### [MixerInputStreamNotExists](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerInputStreamNotExists-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The input stream does not exist. <br>Solutions: Please make sure that the stream corresponding to the entered streamID is being pushed.  




##### [MixerNoOutputTarget](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerNoOutputTarget-constant.md) const int



Description: Illegal parameters exist in mixing task configuration. <br>Cause: 1. The mixing task ID is empty; 2. The mixing room ID is empty; 3. The mixing custom data length exceeds 1000 bytes; 4. The mixing output target stream is empty. <br>Solutions: Please check the configuration parameters of the mixing task.  




##### [MixerNoServices](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerNoServices-constant.md) const int



Description: Does not support the use of stream mixing service. <br>Cause: No stream mixing service configured. <br>Solutions: Please open the service on the console or contact ZEGO business staff.  




##### [MixerNotOwnerStopMixer](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerNotOwnerStopMixer-constant.md) const int



The stream mixing task must be stopped by the user who started the task. This error code is deprecated.  




##### [MixerOutputListInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerOutputListInvalid-constant.md) const int



Description: The output stream list of the stream mixing task is empty. <br>Cause:  The output stream list of the stream mixing task is empty. <br>Solutions: Please check the output stream list of the mixing task.  




##### [MixerOutputTargetInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerOutputTargetInvalid-constant.md) const int



Description: Illegal format of mixed stream output target parameter. <br>Cause: When the target of the mixed stream output target is streamID, an illegal character is passed in. <br>Solutions: Please check whether the target of the mixed stream output target is of streamID type, if so, target only support numbers, English characters and '-', '_'.  




##### [MixerOutputTargetTooLongError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerOutputTargetTooLongError-constant.md) const int



Description: Mixed stream output target is too long. <br>Cause: The length of the target parameter of the mixed stream output exceeds the limit. <br>Solutions: Please make sure that the output destination length does not exceed 1024 bytes.  




##### [MixerStartQpsOverload](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerStartQpsOverload-constant.md) const int



Description: Starts stream mixing tasks too frequently. <br>Cause: Requests are too frequent, exceeding the qps limit of the service. <br>Solutions: Please ensure that the qps of the mixing request is less than 100.  




##### [MixerStartRequestError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerStartRequestError-constant.md) const int



Description: Failed to start the stream mixing task. <br>Cause: Requests are too frequent, exceeding the qps limit of the service. <br>Solutions: Please ensure that the qps of the mixing request is less than 100.  




##### [MixerStopQpsOverload](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerStopQpsOverload-constant.md) const int



Description: Stop stream mixing tasks too frequently. <br>Cause: Requests are too frequent, exceeding the qps limit of the service. <br>Solutions: Please ensure that the qps of the stop mixing request is less than 100.  




##### [MixerStopRequestError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerStopRequestError-constant.md) const int



Description: Failed to stop the stream mixing task. <br>Cause: May be the cause of the network error. <br>Solutions: Please check the network ring.  




##### [MixerTaskIdInvalidCharacter](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerTaskIdInvalidCharacter-constant.md) const int



Description: Invalid mixed flow task ID. <br>Cause: Illegal characters in the stream mixing task ID. <br>Solutions: Stream mixing task ID only supports numbers, English characters and'~','!','@','$','%','^','&amp;','*','(',')', '_','+','=','-','`',';',''',',','.','&lt;','&gt;','/','', please enter the stream mixing task ID in the correct format.  




##### [MixerTaskIdNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerTaskIdNull-constant.md) const int



Description: The mixing task ID is null. <br>Cause: The mixing task ID input when starting mixing task is empty. <br>Solutions: Please enter the correct mixing task ID.  




##### [MixerTaskIdTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerTaskIdTooLong-constant.md) const int



Description: The stream mixing task ID is too long. <br>Cause: The stream mixing task ID is greater than 256 bytes. <br>Solutions: Please enter a mixing task ID less than 256 bytes.  




##### [MixerUserDataTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerUserDataTooLong-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The user-defined data is too long. <br>Solutions: The maximum length of the custom input should not exceed 1000 bytes.  




##### [MixerVideoConfigInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerVideoConfigInvalid-constant.md) const int



Description: The video configuration of the stream mixing task is invalid. <br>Cause:  The video configuration of the stream mixing task is invalid. <br>Solutions: Please check the video configuration of the stream mixing task.  




##### [MixerWatermarkNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerWatermarkNull-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The input image watermark is empty. <br>Solutions: Please enter the correct watermark parameters <a href="../zego_uikit_prebuilt_live_audio_room/ZegoWatermark-class.md">ZegoWatermark</a>.  




##### [MixerWatermarkParametersError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerWatermarkParametersError-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The input image watermark parameter is wrong, it may be that the layout exceeds the canvas range. <br>Solutions: Please enter the correct watermark parameters <a href="../zego_uikit_prebuilt_live_audio_room/ZegoWatermark-class.md">ZegoWatermark</a>.  




##### [MixerWatermarkTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerWatermarkTooLong-constant.md) const int



Description: The mixed stream watermark path is too long. <br>Cause: The length of the mixed stream watermark path parameter exceeds the limit. <br>Solution: Please make sure the watermark path length does not exceed 512 bytes.  




##### [MixerWatermarkUrlInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/MixerWatermarkUrlInvalid-constant.md) const int



Description: Failed to start mixed stream. <br>Cause: The input watermark URL is illegal. <br>Solutions: The watermark URL must start with <code>preset-id://</code> and end with <code>.jpg</code> or <code>.png</code>.  




##### [PlayerCountExceed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerCountExceed-constant.md) const int



Description: Stream playing error.<br>Caution: The number of streams the user attempted to play simultaneously exceeds the maximum number allowed.<br>Solutions: Currently, up to 12 steams can be played at the same time. Please contact ZEGO technical support to increase the capacity if necessary.  




##### [PlayerDecryptionFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerDecryptionFailed-constant.md) const int



Description: Pull stream decryption failed, please check whether the decryption key is correct. <br>Cause: Incorrect decryption key entered. <br>Solutions: Enter the correct decryption key.  




##### [PlayerDecryptionKeyInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerDecryptionKeyInvalid-constant.md) const int



Description: The play stream decryption key is invalid, the key length only supports 16/24/32 bytes. <br>Cause: The input key length is not 16/24/32 bytes. <br>Solutions: Adjust the input key length to 16/24/32 bytes.  




##### [PlayerErrorDispatchAuthError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerErrorDispatchAuthError-constant.md) const int



Description: Play stream authentication is incorrect. <br>Caution: The <code>Token</code> error or timeout required to playing stream across APP. <br>Solutions: Playing the stream to pass the correct <code>Token</code>, or update the <code>Token</code> in time.  




##### [PlayerErrorNetworkInterrupt](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerErrorNetworkInterrupt-constant.md) const int



Description: Stream playing is temporarily interrupted.<br>Caution: Network exception.<br>Solutions: Please wait or check whether the network is normal.  




##### [PlayerErrorPlayStreamWhenUsingMultiRoom](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerErrorPlayStreamWhenUsingMultiRoom-constant.md) const int



Description: Calling the wrong function after enabling the multi-room function causes playing stream fail. <br>Cause: Called the playing stream function that only works for joining a single room mode. <br>Solutions: Please use the function of the same name with ZegoPlayerConfig and specify the room ID to play the stream.  




##### [PlayerErrorPlayStreamWithRoomIdIsNullWhenUsingMultiRoom](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerErrorPlayStreamWithRoomIdIsNullWhenUsingMultiRoom-constant.md) const int



Description: In the multi-room mode, the roomID parameter of the play stream cannot be empty. <br>Cause: The roomID parameter of the pull stream is empty. <br>Solutions: Please enter the correct roomID.  




##### [PlayerErrorServerForbid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerErrorServerForbid-constant.md) const int



Description: Failed to play the stream.<br>Caution: Publishing of this stream is prohibited by backend configuration.<br>Solutions: Please contact ZEGO technical support to solve the problem.  




##### [PlayerInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerInnerError-constant.md) const int



Description: An internal system exception causes a failure to pull the stream. <br>Cause: SDK internal error. <br>Solutions: Please contact ZEGO technical support.  




##### [PlayerNotConfigL3](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerNotConfigL3-constant.md) const int



Description: When using the SDK to play the latency of live streaming, this error code will be returned if you have not subscribed to the low latency live streaming service. <br>Cause: Low-latency live broadcast service is not activated. <br>Solutions: Please contact ZEGO technical support staff to open the low-latency live broadcast service.  




##### [PlayerPlayStreamFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerPlayStreamFailed-constant.md) const int



Description: Stream playing failed.<br>Caution: Possibly due to no data in the stream.<br>Solutions: Check to see if the publish-stream is working or try to play stream again, and if the problem is still not resolved, please contact ZEGO technical support to solve the problem.  




##### [PlayerPlayStreamNotExist](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerPlayStreamNotExist-constant.md) const int



Description: Stream playing failed.<br>Caution: The stream does not exist.<br>Solutions: Please check whether the remote end publish is indeed successful, or whether the publish and play environment are inconsistent.  




##### [PlayerSuperResolutionDeviceNotSupport](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerSuperResolutionDeviceNotSupport-constant.md) const int



Description: This device does not support super resolution. <br>Caution: The device configured on the server does not support super resolution, or the configuration on the server failed to pull. <br>Solutions: replace the device and try again or contact ZEGO technical support.  




##### [PlayerSuperResolutionDevicePerformanceError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerSuperResolutionDevicePerformanceError-constant.md) const int



Description: The performance of super resolution device is not enough.<br>Caution: The performance of device is not enough.<br>Solutions: Please replace the device.  




##### [PlayerSuperResolutionInitingBusyError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerSuperResolutionInitingBusyError-constant.md) const int



Description: Super resolution is initializing, please try again later.<br>Caution: Super resolution is initializing, please try again later.<br>Solutions: Please try again later.  




##### [PlayerSuperResolutionMaxCountExceed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerSuperResolutionMaxCountExceed-constant.md) const int



Description: The number of super resolution streams exceeds the limit.<br>Caution: The number of super resolution streams exceeds the limit.<br>Solutions: Currently, super resolution support up to 1 playing steam at the same time.  




##### [PlayerSuperResolutionVideoSizeNotSupport](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerSuperResolutionVideoSizeNotSupport-constant.md) const int



Description: The number of super resolution streams exceeds the limit.<br>Caution: The number of super resolution streams exceeds the limit.<br>Solutions: contact ZEGO technical support.  




##### [PlayerTakePlayStreamSnapshotFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerTakePlayStreamSnapshotFailed-constant.md) const int



Description: Failed to capture the screenshot of the streaming screen, please check whether the stream to be captured is normal. <br>Cause: The stream is not pulled. <br>Solutions: Check whether it starts to play the stream, and whether there is an abnormality in the process of playing the stream.  




##### [PlayerVideoDecoderFail](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerVideoDecoderFail-constant.md) const int



Description: Video decoder fail.<br>Caution: Video decoder fail.<br>Solutions: Please contact ZEGO technical support.  




##### [PlayerVideoDecoderNoSupportted](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PlayerVideoDecoderNoSupportted-constant.md) const int



Description: Unsupported video decoder.<br>Caution: There is no selected video decoder in the current SDK.<br>Solutions: Please contact ZEGO technical support.  




##### [PreprocessBeautifyOptionInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessBeautifyOptionInvalid-constant.md) const int



Description: Failed to set the beauty configuration. <br>Cause: The incoming beauty parameters are incorrect. <br>Solutions: Please check the passed in <a href="../zego_uikit_prebuilt_live_audio_room/ZegoBeautifyOption-class.md">ZegoBeautifyOption</a> type parameter.  




##### [PreprocessElectronicEffectsTonalInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessElectronicEffectsTonalInvalid-constant.md) const int



Description: Failed to turn on or turn off the electronic sound effect. <br>Cause: the initial pitch parameter tonal of the electronic tone is invalid. <br>Solutions: The normal range of the starting pitch parameter of the electronic tone is 0 ~ 11.  




##### [PreprocessEnableEffectsBeautyFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessEnableEffectsBeautyFailed-constant.md) const int



Description: Failed to turn on or turn off the beauty effect. <br>Cause: The beauty environment is not activated. <br>Solutions: Please call <code>startEffectsEnv</code> to start the beauty environment first.  




##### [PreprocessEnableEffectsEnvFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessEnableEffectsEnvFailed-constant.md) const int



Description: Failed to open or close the beauty environment. <br>Cause: The beauty environment was not turned on or off before the engine started. <br>Solutions: Please make sure to turn on or turn off the beauty environment before the engine starts, for example: before calling (startPreview), (startPublishingStream), (startPlayingStream), (createMediaPlayer) or (createAudioEffectPlayer).  




##### [PreprocessNotSupportEffectsBufferType](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessNotSupportEffectsBufferType-constant.md) const int



Description: Effects Beauty does not support the currently set video data type. <br>Cause: <code>enableCustomVideoProcessing</code> interface, Windows platform only supports raw_data, Apple device only supports cv_pixel_buffer, Android platform supports gl_texture_2d. <br>Solutions: select the correct video data type.  




##### [PreprocessPreprocessUnknownError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessPreprocessUnknownError-constant.md) const int



Description: Unknown error of the pre-processing module. <br>Solutions: Please contact ZEGO technical support.  




##### [PreprocessReverbEchoParamInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessReverbEchoParamInvalid-constant.md) const int



Description: Set reverberation echo parameters failed . <br>Cause: The reverberation echo parameters is invalid. <br> Solutions: Input the correct reverb echo parameters <code>setReverbEchoParam</code>.  




##### [PreprocessReverbEchoParamNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessReverbEchoParamNull-constant.md) const int



The reverberation echo parameters is null. Please check the input parameter.  




##### [PreprocessReverbParamDampingInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessReverbParamDampingInvalid-constant.md) const int



Description: Failed to set the reverberation parameters. <br>Cause: the reverberation damping parameter is invalid. <br>Solutions: The normal range of the reverberation damping parameter is 0.0 ~ 2.0  




##### [PreprocessReverbParamDryWetRatioInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessReverbParamDryWetRatioInvalid-constant.md) const int



Description: Failed to set the reverberation parameters. <br>Cause: The dry_wet_ratio parameter of the reverberation is invalid. <br>Solutions: The normal range of the dry_wet_ratio parameter of reverberation is greater than 0.0  




##### [PreprocessReverbParamNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessReverbParamNull-constant.md) const int



The reverberation parameter is null. Please check the input parameter. This error code is deprecated.  




##### [PreprocessReverbParamReverberanceInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessReverbParamReverberanceInvalid-constant.md) const int



Description: Failed to set the reverberation parameters. <br>Cause: The reverberance parameter is invalid. <br>Solutions: The normal range of the reverberance parameter is 0.0 ~ 0.5  




##### [PreprocessReverbParamRoomSizeInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessReverbParamRoomSizeInvalid-constant.md) const int



Description: Failed to set the reverberation parameters. <br>Cause: the reverberation room size parameter is invalid. <br>Solutions: The normal range of the reverberation room size parameter is 0.0 ~ 1.0  




##### [PreprocessSetEffectsParamFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessSetEffectsParamFailed-constant.md) const int



Description: Failed to set beauty parameters. <br>Cause: The beauty environment is not activated. <br>Solutions: Please call <code>startEffectsEnv</code> to start the beauty environment first.  




##### [PreprocessVirtualStereoAngleInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessVirtualStereoAngleInvalid-constant.md) const int



Description: Failed to start virtual stereo. <br>Cause: The virtual stereo angle parameter is invalid. <br>Solutions: The normal range of angle parameter is -1 ~ 360.  




##### [PreprocessVoiceChangerParamInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessVoiceChangerParamInvalid-constant.md) const int



Description: Failed to set the voice changing parameters. <br>Cause: The param setting of the voice changing parameter is invalid. <br>Solutions: The normal range of parameter param is -12.0 ~ 12.0  




##### [PreprocessVoiceChangerParamNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PreprocessVoiceChangerParamNull-constant.md) const int



The voice changer parameter is null. Please check the input parameter. This error code is deprecated.  




##### [PublisherAudioSideDataNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherAudioSideDataNull-constant.md) const int



Description: Failed to send audio side info. <br>Cause: data is empty. <br>Solutions: Incoming non-empty data.  




##### [PublisherAudioSideDataTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherAudioSideDataTooLong-constant.md) const int



Description: Failed to send audio side info. <br>Cause: The input data exceeds the length limit. <br>Solutions: The length of the sent audio side data should be less than 1024 bytes.  




##### [PublisherBitrateInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherBitrateInvalid-constant.md) const int



Description: Publishing failed due to wrong bitrate setting.<br>Cause: The set video bitrate, audio bitrate, or minimum video bitrate threshold for traffic control exceeds the upper limit.<br>Solutions: Please check if the bitrate value is in the correct unit (kbps).Adjust the bitrate setting.  




##### [PublisherEncryptionKeyInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherEncryptionKeyInvalid-constant.md) const int



Description: The publish stream encryption key is invalid.<br>Caution: The set encryption key length is not supported.<br>Solutions: The Publish-stream encryption key length to be 16/24/32 bytes.  




##### [PublisherErrorAlreadyDoPublish](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorAlreadyDoPublish-constant.md) const int



Description: Failed to publish the stream. The publish channel is already publishing streams.<br>Cause:  The publish channel is already publishing streams.<br>Solutions: Please check the business logic to avoid repeating the publish for publish channel which is publishing.  




##### [PublisherErrorDispatchAuthError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorDispatchAuthError-constant.md) const int



Description: Push-pull flow authentication is incorrect. <br>Caution: An <code>appSign</code> error was passed when creating the engine, or a Token error or timeout was passed when logging into the room. <br>Solutions: Pass the correct <code>Token</code> upon login, or invoke <code>renewToken</code> when recive <code>onRoomTokenWillExpire</code> callback.  




##### [PublisherErrorH265EncoderNotSupported](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorH265EncoderNotSupported-constant.md) const int



Description: Streaming failed, H.265 encoding is not supported.<br>Cause: The hardware device does not support H.265 encoding, or the SDK does not include H.265 encoding module.<br>Solutions: Contact ZEGO technical support to confirm whether the SDK contains the H.265 encoding module, if the hardware device does not support it, it is recommended to upgrade the hardware.  




##### [PublisherErrorNetworkInterrupt](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorNetworkInterrupt-constant.md) const int



Description:Stream publishing is temporarily interrupted and is retrying. <br>Cause: The network fluctuates or the network signal is bad.<br>Solutions: Please wait or check whether the network is normal.  




##### [PublisherErrorPublishWhenUsingMultiRoom](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorPublishWhenUsingMultiRoom-constant.md) const int



Description: StartPlayingStream failed.<br>Caution: In multi-room mode, the publish-stream function is called incorrectly.<br>Solutions: In multi-room mode, A publish-stream function with the parameter 'ZegoPublisherConfig' needs to be called.  




##### [PublisherErrorPublishWithRoomIdIsNullWhenUsingMultiRoom](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorPublishWithRoomIdIsNullWhenUsingMultiRoom-constant.md) const int



Description: StartPlayingStream failed.<br>Caution: In multi-room mode, the publish-stream function is called incorrectly.<br>Solutions: In multi-room mode, A publish-stream function parameter 'roomID' cannot be empty.  




##### [PublisherErrorRepetitivePublishStream](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorRepetitivePublishStream-constant.md) const int



Description: Failed to publish the stream. The same stream already exists in the room.<br>Cause: The same stream already exists in the room.<br>Solutions: Replace with a new stream ID. Adjust the stream ID generation strategy to ensure uniqueness.  




##### [PublisherErrorRetryTimeout](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorRetryTimeout-constant.md) const int



Description: Stream publish retry has exceeds the maximum retry time.<br>Cause: The the network signal is bad, and the maximum retry time is exceeded.<br>Solutions: Check the network status or switch to another network.  




##### [PublisherErrorServerForbid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherErrorServerForbid-constant.md) const int



Description: Failed to publish the stream. Publishing of this stream is prohibited by backend configuration.<br>Cause: Publishing of this stream is prohibited by backend configuration.<br>Solutions: Contact ZEGO technical support to deal with it.  




##### [PublisherExtraInfoNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherExtraInfoNull-constant.md) const int



The extra info of the stream is null.  




##### [PublisherExtraInfoTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherExtraInfoTooLong-constant.md) const int



The extra info of the stream is too long. The maximum length should be less than 1024 bytes.  




##### [PublisherInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherInnerError-constant.md) const int



Description: Stream publishing failed due to system internal exceptions.<br>Caution: Stream publishing failed due to system internal exceptions.<br>Solutions: Please contact ZEGO technical support to solve the problem.  




##### [PublisherPublishStreamFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherPublishStreamFailed-constant.md) const int



Description: Publishing failed due to no data in the stream.<br>Cause: No data in the stream.<br>Solutions: Check whether the video, audio capture module is working properly.  




##### [PublisherRtmpServerDisconnect](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherRtmpServerDisconnect-constant.md) const int



Description: Failed to publish the stream. The connection to the RTMP server is interrupted.<br>Cause: The publish address is wrong, or the network signal is bad.<br>Solutions: Please check whether there is any problem with the network connection or the stream publishing URL.  




##### [PublisherSeiDataNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherSeiDataNull-constant.md) const int



Description: Failed to send SEI. <br>Cause: data is empty. <br>Solutions: Incoming non-empty data.  




##### [PublisherSeiDataTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherSeiDataTooLong-constant.md) const int



Description: Failed to send SEI. <br>Cause: The input data exceeds the length limit. <br>Solutions: The length of the sent SEI data should be less than 4096 bytes.  




##### [PublisherTakePublishStreamSnapshotFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherTakePublishStreamSnapshotFailed-constant.md) const int



Description: Failed to take a screenshot of the publis stream screen. <br>Cause: The preview is stopped and the push is abnormal. <br>Solutions: Turn on preview or re-publish.  




##### [PublisherTrafficModeInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherTrafficModeInvalid-constant.md) const int



Description: The property param of the traffic control is set incorrectly.<br>Cause: The property param of the traffic control is less than 0 or exceeds all combinations.<br>Solutions: Check the settings of the property param of the traffic control.  




##### [PublisherUpdateCdnTargetError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherUpdateCdnTargetError-constant.md) const int



Description: Failed to update the relay CDN status. <br>Cause: The URL of the relay address is incorrect. <br>Solutions: Check whether the input URL is valid.  




##### [PublisherUpdateExtraInfoFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherUpdateExtraInfoFailed-constant.md) const int



Failed to update the extra info of the stream. Please check the network connection.  




##### [PublisherVideoEncoderFail](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherVideoEncoderFail-constant.md) const int



Description: Video encoder error.<br>Caution: Video encoder error.<br>Solutions: Please contact ZEGO technical support.  




##### [PublisherVideoEncoderNoSupportted](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherVideoEncoderNoSupportted-constant.md) const int



Description: Unsupported video encoder.<br>Caution: There is no selected video encoder in the current SDK.<br>Solutions: Please contact ZEGO technical support.  




##### [PublisherWatermarkLayoutInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherWatermarkLayoutInvalid-constant.md) const int



Description: Incorrect watermark layout.<br>Caution: The layout area exceed the encoding resolution.<br>Solutions: Make sure the layout area cannot exceed the encoding resolution and call current interface.  




##### [PublisherWatermarkUrlInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherWatermarkUrlInvalid-constant.md) const int



Description: Failed to set publish watermark. <br>Cause: The incoming watermark path was entered incorrectly or the image format is not supported. <br>Solutions: Incoming the correct watermark path, only <code>jpg</code> and <code>png</code> image formats are supported.  




##### [PublisherWatermarkUrlNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherWatermarkUrlNull-constant.md) const int



Description: Failed to set publish watermark. <br>Cause: The incoming watermark path is empty. <br>Solutions: Incoming non-empty path.  




##### [PublisherWatermarkUrlTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/PublisherWatermarkUrlTooLong-constant.md) const int



Description: Failed to set publish watermark. <br>Cause: The incoming watermark path exceeds the byte size limit. <br>Solutions: The incoming watermark path should be less than 1024 bytes.  




##### [RangeAudioExceedMaxCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeAudioExceedMaxCount-constant.md) const int



Description: Failed to create range audio. <br>Cause: The instance exceeds the maximum limit. <br>Solutions: Use the used range audio example.  




##### [RangeAudioNoInstance](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeAudioNoInstance-constant.md) const int



Description: The function call failed. <br>Cause: No range auido instance has been created. <br>Solutions: Create a range audio instance.  




##### [RangeAudioNotSupportMultiRoom](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeAudioNotSupportMultiRoom-constant.md) const int



Description: Failed to create range voice. <br>Cause: Range voice cannot be used in multi-room mode. <br>Solutions: Set the single-party mode.  




##### [RangeAudioTeamIdInvalidCharacter](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeAudioTeamIdInvalidCharacter-constant.md) const int



Description: Failed to set the team ID.<br>Cause: The input user ID contains invalid characters. <br>Solutions: User ID can only contains numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', ',', '.', '&lt;', '&gt;', '/', ''.  




##### [RangeAudioTeamIdTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeAudioTeamIdTooLong-constant.md) const int



Description: Failed to set the team ID. <br>Cause: The input team ID exceeds the maximum limit. <br>Solutions: The input string is less than 64 bytes.  




##### [RangeSceneCallFunctionFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneCallFunctionFailed-constant.md) const int



Description: Calling function failed. <br>Cause: Illegal parameter or SDK does not contain RangeScene module. <br>Solutions: Please confirm whether the SDK contains the RangeScene module and check the parameters.  




##### [RangeSceneCoordinateOutOfRange](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneCoordinateOutOfRange-constant.md) const int



Description: Coordinates out of range. <br>Cause: Coordinates out of scene range. <br>Solutions: Please pass in the correct coordinates.  




##### [RangeSceneExceedMaxCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneExceedMaxCount-constant.md) const int



Description: The number of RangeScene instances exceeds the maximum number allowed. <br>Cause: The number of RangeScene instances exceeds the maximum number allowed. Up to 1 instances can be created. <br> Solutions: RangeScene can create up to 1 instances, and make sure that the number of RangeScene instances is not exceeded the maximum limit.  




##### [RangeSceneInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneInnerError-constant.md) const int



Description: Failed due to internal system exceptions.<br>Cause: Unknown internal error.<br>Solutions: Contact ZEGO technical support to deal with it.  




##### [RangeSceneItemBindExceedLimit](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneItemBindExceedLimit-constant.md) const int



Description: The item binding user exceeds the maximum limit. <br>Cause: The item binding user exceeds the maximum limit. <br>Solutions: The item binding user exceeds the maximum limit. Please try again later.  




##### [RangeSceneItemCapacityExceedLimit](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneItemCapacityExceedLimit-constant.md) const int



Description: The binding capacity of the item exceeds the maximum limit. <br>Cause: The binding capacity of the item exceeds the maximum limit. <br>Solutions: Please use a capacity that does not exceed the maximum binding capacity to create an item.  




##### [RangeSceneItemCasFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneItemCasFailed-constant.md) const int



Description: The item has been operated by others. <br>Cause: The item has been operated by others. <br>Solutions: Please try again later.  




##### [RangeSceneItemHasBeenCreated](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneItemHasBeenCreated-constant.md) const int



Description: The item has been created. <br>Cause: The item has been created. <br>Solutions: The item has been created. You don't need to create it again.  




##### [RangeSceneItemNotBind](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneItemNotBind-constant.md) const int



Description: The item is not bound. <br>Cause: The item is not bound. <br>Solutions: Please bind the item first.  




##### [RangeSceneItemNotExist](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneItemNotExist-constant.md) const int



Description: The item does not exist. <br>Cause: The item does not exist. <br>Solutions: Please create an item first.  




##### [RangeSceneItemOutOfUserView](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneItemOutOfUserView-constant.md) const int



Description: The item is beyond the user's view. <br>Cause: The item is beyond the user's view. <br>Solutions: Please operate the item within the user's view.  




##### [RangeSceneNetworkInterrupt](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneNetworkInterrupt-constant.md) const int



Description: Scene connection is temporarily interrupted. <br>Cause: Possibly due to network problems. <br>Solutions: Please wait or check whether the network is normal.  




##### [RangeSceneNoInstance](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneNoInstance-constant.md) const int



Description: The RangeScene instance not created. <br>Cause: The RangeScene instance not created. <br> Solutions: Create a RangeScene instance before using RangeScene <code>createRangeScene</code>.  




##### [RangeSceneNotLoginScene](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneNotLoginScene-constant.md) const int



Description: Not login scene. <br>Cause: Not login scene. <br> Solutions: Please call <code>loginScene</code> to login scene.  




##### [RangeSceneNotSupport](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneNotSupport-constant.md) const int



Description: Use not support feature. <br>Cause: Use the status synchronization interface when the status synchronization function is not enabled. <br> Solutions: To use the status synchronization interface, please enable the status synchronization function.  




##### [RangeSceneRetryTimeout](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneRetryTimeout-constant.md) const int



Description: Scene login retry has exceeded the maximum retry time. <br>Cause: Possibly due to network problems. <br>Solutions: Please check whether the network is working or switch the network environment.  




##### [RangeSceneTeamExceedMaxCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneTeamExceedMaxCount-constant.md) const int



Description: The number of joined RangeScene teams exceeds the maximum number allowed. <br>Cause: The number of joined RangeScene teams exceeds the maximum number allowed. Up to 5 are allowed by default. <br> Solutions: RangeScene teams can joined are up to 5, and make sure that the number of RangeScene teams joned is not exceeded the maximum limit.  




##### [RangeSceneTeamIdIncorrect](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneTeamIdIncorrect-constant.md) const int



Description: Team id not exist. <br>Cause: Use incorrect team id when leave team. <br> Solutions: Use correct team id when leave team.  




##### [RangeSceneTeamIdOccupied](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneTeamIdOccupied-constant.md) const int



Description: Team id already been used. <br>Cause: The team id already been used when join team. <br> Solutions: Use a new team id to join team.  




##### [RangeSceneTokenExpire](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneTokenExpire-constant.md) const int



Description: Token expire. <br>Cause: Token expire or the generated Token validity period parameter type is incorrect. <br>Solutions: Regenerate the Token.  




##### [RangeSceneTokenIllegal](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneTokenIllegal-constant.md) const int



Description: Token verification failed. <br>Cause: The parameters passed in during token generation are inconsistent with the SDK. <br>Solutions: Please use the correct token regenerated.  




##### [RangeSceneUserBindItemExceedLimit](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RangeSceneUserBindItemExceedLimit-constant.md) const int



Description: The user has bound the item to the maximum limit. <br>Cause: The user has bound the item to the maximum limit. <br>Solutions: Please unbind some items that do not need to be operated temporarily.  




##### [RecorderCommonLiveroomApiError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderCommonLiveroomApiError-constant.md) const int



Description: Generic recording API error. <br>Cause: Invalid input parameter. <br> Solutions: Please check the record file path parameter or the record file format parameter is valid or not.  




##### [RecorderFileHandleExceptions](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderFileHandleExceptions-constant.md) const int



Description: File handle exception. <br>Cause: File handle exception. <br> Solutions: Please contact ZEGO technical support.  




##### [RecorderFilePathTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderFilePathTooLong-constant.md) const int



Description: The specified recorded file path is too long. <br>Cause: The specified recorded file path is too long. The maximum length should be less than 1024 bytes. <br> Solutions: Please specify recorded file path less than 1024 bytes.  




##### [RecorderFileSuffixNameFormatNotSupport](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderFileSuffixNameFormatNotSupport-constant.md) const int



Description: the file name suffix is not supported. <br>Cause: the file name suffix is not supported. <br>Solutions: only support .mp4/.aac/.flv.  




##### [RecorderInnerVeError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderInnerVeError-constant.md) const int



Description: SDK internal error. <br>Cause: Internal error. <br> Solutions: Please contact ZEGO technical support.  




##### [RecorderIoExceptions](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderIoExceptions-constant.md) const int



Description: I/O exception. <br>Cause: I/O exception. <br> Solutions: Please contact ZEGO technical support.  




##### [RecorderNoEnoughSpareCapacity](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderNoEnoughSpareCapacity-constant.md) const int



Description: Insufficient disk space. <br>Cause: Insufficient disk space. <br> Solutions: Please ensure sufficient disk space.  




##### [RecorderOpenFileFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderOpenFileFailed-constant.md) const int



Description: Open file failed. <br>Cause: Invalid file path or no permissions to read/write file. <br> Solutions: Please specify a valid file path and has proper permissions to read/write.  




##### [RecorderWriteFileError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RecorderWriteFileError-constant.md) const int



Description: Write file failed. <br>Cause: No permissions to write file. <br> Solutions: Please specify a valid file path and has proper permissions to write.  




##### [RoomAppCallApiTooFrequent](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomAppCallApiTooFrequent-constant.md) const int



Description: The interface is called more frequently than the upper limit. <br>Cause: This application calls this interface too often. <br>Solutions: Please control the frequency of calls to this interface. Please refer to <a href="https://docs.zegocloud.com/article/7612">https://docs.zegocloud.com/article/7612</a> for details.  




##### [RoomAppCallTooFrequent](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomAppCallTooFrequent-constant.md) const int



Description: Room signalling type interfaces are called more frequently than the upper limit. <br>Cause: This application calls the room signalling type interface too often. (e.g., <code>sendCustomCommand</code> <code>sendBroadcastMessage</code>) <br>Solutions: Please control the frequency of application calls to the room signalling type interface. Please refer to <a href="https://docs.zegocloud.com/article/7612">https://docs.zegocloud.com/article/7612</a> for details.  




##### [RoomConnectTemporaryBroken](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomConnectTemporaryBroken-constant.md) const int



Description: Room connection is temporarily interrupted and is retrying. <br>Cause: Possibly due to network problems. <br>Solutions: Please wait or check whether the network is normal.  




##### [RoomCountExceed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomCountExceed-constant.md) const int



Description: The number of rooms the user attempted to log into simultaneously exceeds the maximum number allowed. Currently, a user can only be logged in to one main room.<br>Cause: In single-room mode, log in to multiple main rooms at the same time (including repeated calls to log in to the same room A without exiting room A). <br>Solutions: Please check is login multiple rooms simultaneously or not under single room mode.  




##### [RoomDisconnect](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomDisconnect-constant.md) const int



Description: Room connection disconnected. <br>Cause: Possibly due to network problems. <br>Solutions: Please check whether the network is working or switch the network environment.  




##### [RoomErrorAuthenticationFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomErrorAuthenticationFailed-constant.md) const int



Description: Room login authentication failed. <br>Cause: login set token error or token expired. <br> Solutions: set new token.  




##### [RoomErrorConnectFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomErrorConnectFailed-constant.md) const int



Description: Login failed, possibly due to network problems. <br>Cause: The current network is abnormal. <br> Solutions: It is recommended to switch the network to try.  




##### [RoomErrorExceedMaximumMember](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomErrorExceedMaximumMember-constant.md) const int



Description: The number of users logging into the room exceeds the maximum number of concurrent users configured for the room. (In the test environment, the default maximum number of users in the room is 50). <br>Cause: too much user in room. <br> Solutions: contact ZEGO technical support.  




##### [RoomErrorExceedMaximumRoomCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomErrorExceedMaximumRoomCount-constant.md) const int



Description: in test environment The total number of rooms logged in at the same time exceeds the limit. (In the test environment, the maximum number of concurrent rooms is 10). <br>Cause: Too many rooms logged in at the same time. <br> Solutions: logout some room, login room.  




##### [RoomErrorLoginMultiRoomNotOpen](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomErrorLoginMultiRoomNotOpen-constant.md) const int



Description: login failed, multi-room mode is not activate. <br>Cause: multi-room mode is not activate. <br> Solutions: please contact ZEGO technical support.  




##### [RoomErrorLoginTimeout](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomErrorLoginTimeout-constant.md) const int



Description: Login timed out, possibly due to network problems. <br>Cause: The current network delay is large. <br> Solutions: It is recommended to switch the network to try.  




##### [RoomErrorMultiRoomExceedMaximumRoomCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomErrorMultiRoomExceedMaximumRoomCount-constant.md) const int



The total number of rooms logged in at the same time exceeds the limit, Please contact ZEGO technical support.  




##### [RoomInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomInnerError-constant.md) const int



Description: Room login failed due to internal system exceptions.<br>Cause: Unknown internal error.<br>Solutions: Contact ZEGO technical support to deal with it.  




##### [RoomKickedOut](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomKickedOut-constant.md) const int



Description: The user was kicked out of the room. <br>Cause: Possibly because the same user ID is logged in on another device. <br>Solutions: Use a unique user ID.  




##### [RoomManualKickedOut](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomManualKickedOut-constant.md) const int



Description: The business server has sent a signal to kick the user out of the room. <br>Cause: The business server has sent a signal to kick the user out of the room. <br>Solutions: Contact the business server for processing.  




##### [RoomMultiRoomDeprecated](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomMultiRoomDeprecated-constant.md) const int



Description: This method has been deprecated after version 2.9.0. <br>Cause: This method has been deprecated after version 2.9.0. <br>Solutions: Please set <code>setRoomMode</code> to select multi-room mode before the engine started, and then call <code>loginRoom</code> to use multi-room.  




##### [RoomMultiRoomLoginUserNotSame](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomMultiRoomLoginUserNotSame-constant.md) const int



Description: set multi room mode, userID or user name is different. <br>Cause: set multi room mode, login multi room use different user id or user name. <br> Solutions: Currently supports at most one key, if you need to support multiple, contact ZEGO technical support.  




##### [RoomMultiRoomRequired](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomMultiRoomRequired-constant.md) const int



Description: Multi-room mode required. <br>Cause: Wrong room mode been used, e.g. single-room. <br>Solutions: Please use <code>setRoomMode</code> to select multi-room mode before the engine started.  




##### [RoomMultiRoomSwtichRoomInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomMultiRoomSwtichRoomInvalid-constant.md) const int



Description: The <code>switchRoom</code> function cannot be used in multi-room mode. <br>Cause: multi room mode SDK not support. <br> Solutions: first call <code>logoutRoom</code> then call <code>loginRoom</code>.  




##### [RoomNoMultiRoomPermission](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomNoMultiRoomPermission-constant.md) const int



Description: No multi-room permission. <br>Cause: No multi-room permission. <br>Solutions: Please contact ZEGO technical support to enable it.  




##### [RoomNoToken](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomNoToken-constant.md) const int



Description: This error code is returned if the user does not pass <code>AppSign</code> when creating the engine or <code>Token</code> when logging in to the room. <br>Cause: The Token is not transmitted in the login room. <br>Solutions: Set the <code>Token</code> when you login to the room.  




##### [RoomRetryTimeout](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRetryTimeout-constant.md) const int



Description: Room login retry has exceeded the maximum retry time. <br>Cause: Possibly due to network problems. <br>Solutions: Please check whether the network is working or switch the network environment.  




##### [RoomRoomCallApiTooFrequent](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomCallApiTooFrequent-constant.md) const int



Description: The frequency of calls to the interface by users in the room exceeds the upper limit. <br>Cause: The interface is called too often by users in the room. <br>Solutions: Please control the frequency of calls to this interface by users in the room. Please refer to <a href="https://docs.zegocloud.com/article/7612">https://docs.zegocloud.com/article/7612</a> for details.  




##### [RoomRoomExtraInfoExceedKeys](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomExtraInfoExceedKeys-constant.md) const int



Description: The number of keys set in the room additional message exceeds the maximum number of supported limits. <br>Cause: called setRoomExtraInfo Different keys have been passed in multiple times. <br> Solutions: please contact ZEGO technical support.  




##### [RoomRoomExtraInfoKeyEmpty](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomExtraInfoKeyEmpty-constant.md) const int



The key for room extra info is empty. <br>The key for room extra info entered by the <code>setRoomExtraInfo</code> function is empty. <br>Please check the key for room extra info entered when calling the <code>setRoomExtraInfo</code> function to make sure it is not empty.  




##### [RoomRoomExtraInfoKeyTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomExtraInfoKeyTooLong-constant.md) const int



The key for room extra info is too long. <br>The length of the key for room extra info input by the <code>setRoomExtraInfo</code> function is greater than or equal to 128 bytes. <br>Please check the key for room extra info entered when calling the <code>setRoomExtraInfo</code> function to ensure that its length is less than 128 bytes.  




##### [RoomRoomExtraInfoValueTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomExtraInfoValueTooLong-constant.md) const int



The value for room extra info is too long. <br>The length of the value for room extra info input by the <code>setRoomExtraInfo</code> function is greater than or equal to 4096 bytes. <br>Please check the value for room extra info entered when calling the <code>setRoomExtraInfo</code> function to ensure that its length is less than 4096 bytes.  




##### [RoomRoomIdHasBeenUsed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomIdHasBeenUsed-constant.md) const int



Description: The room ID has been used by other login room interface. Current user can not login room with the room ID before release the room ID. <br>Cause: The room ID has been used by other login room interface. <br>Solutions: Logout the room with the same room ID first.  




##### [RoomRoomidIncorrect](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomidIncorrect-constant.md) const int



Description: Haven't login with the input room ID.<br>Cause: Haven't login with the input room ID before call <code>logoutRoom</code> or <code>switchRoom</code> or <code>renewToken</code> or <code>setRoomExtraInfo</code>. <br>Solutions: Please check has login with the room ID or not.  




##### [RoomRoomidInvalidCharacter](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomidInvalidCharacter-constant.md) const int



The input room ID contains invalid characters. <br>The room ID entered by the <code>loginRoom</code> function contains illegal characters.<br>Please check the room ID entered when calling the <code>loginRoom</code> function to ensure that it is only contain numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', ',', '.', '&lt;', '&gt;', '/', ''.  




##### [RoomRoomidNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomidNull-constant.md) const int



The input room ID is empty. <br>The room ID entered by the <code>loginRoom</code> function is empty. <br>Please check the room ID entered when calling the <code>loginRoom</code> function to make sure it is not empty.  




##### [RoomRoomidTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomRoomidTooLong-constant.md) const int



The input room ID is too long. <br>The length of the room ID input by the <code>loginRoom</code> function is greater than or equal to 128 bytes. <br>Please check the room ID entered when calling the <code>loginRoom</code> function to ensure that its length is less than 128 bytes.  




##### [RoomTokenAppidError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomTokenAppidError-constant.md) const int



Description: Token Appid error. <br>Cause: The generated Token Appid is inconsistent with the SDK used Appid, Or the appID type is incorrect. <br>Solutions: Use the Appid of the generated Token.  




##### [RoomTokenExpireError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomTokenExpireError-constant.md) const int



Description: Token expire. <br>Cause: Token expire Or the generated Token validity period parameter type is incorrect. <br>Solutions: Regenerate the Token.  




##### [RoomTokenFormatError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomTokenFormatError-constant.md) const int



Description: Token Format error. <br>Cause: The generated Token transmission parameter payload is in non-JSON format. <br>Solutions: The payload is correctly transmitted in json format when the Token is generated.  




##### [RoomTokenInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomTokenInnerError-constant.md) const int



Description: Token inner error. <br>Cause:  Unknown internal error. <br>Solutions: Contact ZEGO technical support to deal with it..  




##### [RoomTokenNoncetypeError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomTokenNoncetypeError-constant.md) const int



Description: The Token Nonce parameter type is incorrect. <br>Cause: The nonce parameter type of the generated Token is incorrect. <br>Solutions: Ensure that nonce is int64 data.  




##### [RoomTokenUseridError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomTokenUseridError-constant.md) const int



Description: Token userID error. <br>Cause: The generated Token userID is inconsistent with the login used userID Or the userID type is incorrect. <br>Solutions: Login using the userID that generates the Token.  




##### [RoomTokenVersionError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomTokenVersionError-constant.md) const int



Description: Token version error. <br>Cause: Description The Token Version was generated incorrectly. <br>Solutions: Generate the Token with the correct version.  




##### [RoomUserIdInvalidCharacter](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomUserIdInvalidCharacter-constant.md) const int



Description: The input user ID contains invalid characters.<br>Cause: The input user ID contains invalid characters. <br>Solutions: User ID can only contains numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', ',', '.', '&lt;', '&gt;', '/', ''.  




##### [RoomUserIdNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomUserIdNull-constant.md) const int



Description: The input user ID is empty.<br>Cause: The input user ID is empty. <br>Solutions: Please check the input user ID is empty or not.  




##### [RoomUserIdTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomUserIdTooLong-constant.md) const int



The input user ID is too long. <br>The length of the user ID input by the <code>loginRoom</code> function is greater than or equal to 64 bytes. <br>Please check the user ID entered when calling the <code>loginRoom</code> function to ensure that its length is less than 64 bytes.  




##### [RoomUserInBlacklist](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomUserInBlacklist-constant.md) const int



Description: If the user is in the server blacklist when logging in to the room, this error code will be returned, indicating that it is forbidden to log in to the room. <br>Cause: The user is currently in the server blacklist. <br>Solutions: Please contact ZEGO technical support.  




##### [RoomUserNameInvalidCharacter](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomUserNameInvalidCharacter-constant.md) const int



The input user name contains invalid characters. <br>The user name entered by the <code>loginRoom</code> function contains illegal characters.<br>Please check the user name entered when calling the <code>loginRoom</code> function to ensure that it is only contain numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', ',', '.', '&lt;', '&gt;', '/', ''.  




##### [RoomUserNameNull](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomUserNameNull-constant.md) const int



The input user name is empty. <br>The user name entered by the <code>loginRoom</code> function is empty. <br>Please check the user name entered when calling the <code>loginRoom</code> function to make sure it is not empty.  




##### [RoomUserNameTooLong](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomUserNameTooLong-constant.md) const int



The input user name is too long. <br>The length of the user name input by the <code>loginRoom</code> function is greater than or equal to 256 bytes. <br>Please check the user name entered when calling the <code>loginRoom</code> function to ensure that its length is less than 256 bytes.  




##### [RoomWrongLoginSequence](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomWrongLoginSequence-constant.md) const int



Description: Wrong order of login rooms. <br>Cause: Log in multi room without log in the main room. <br>Solutions: Please log in to the main room with <code>loginRoom</code> before logging in to multi room.  




##### [RoomWrongLogoutSequence](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/RoomWrongLogoutSequence-constant.md) const int



Description: Wrong order of logout rooms. <br>Cause: Log out the main room without log out multi room. <br>Solutions: Please log out of the multi room before logging out of the main room.  




##### [ScreenCaptureExceedMaxCount](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/ScreenCaptureExceedMaxCount-constant.md) const int



Description: Failed to create screen capture source. <br>Cause: The instance exceeds the maximum limit. <br>Solutions: Use an existing screen capture instance or destroy the previous instance.  




##### [ScreenCaptureNoInstance](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/ScreenCaptureNoInstance-constant.md) const int



Description: The function call failed. <br>Cause: No screen capture source instance has been created. <br>Solutions: Create a screen capture source instance.  




##### [ScreenCaptureNotSupport](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/ScreenCaptureNotSupport-constant.md) const int



Description: Startup screen capture failed. <br>Cause: The current system version does not support screen capture. <br>Solutions: Use system version above Android 5 (API level 21).  




##### [ScreenCapturePermissionDenied](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/ScreenCapturePermissionDenied-constant.md) const int



Description: Startup screen capture failed. <br>Cause: The user refused to grant the app screen capture permission. <br>Solutions: Allow the app to capture screen permissions.  




##### [ScreenCaptureSdkNoModule](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/ScreenCaptureSdkNoModule-constant.md) const int



Description: Startup screen capture failed. <br>Cause: Unable to share the screen module. <br>Solutions: Please introduce screen sharing module resources, or contact technical support.  




##### [UtilitiesNetworkConnectivityTestFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesNetworkConnectivityTestFailed-constant.md) const int



Description: Network connectivity test failed. <br>Cause: Not connected to the network. <br> Solutions: Please check if you can access the Internet properly.  




##### [UtilitiesNetworkToolConnectServerFailed](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesNetworkToolConnectServerFailed-constant.md) const int



Description: Network speed test connection failure. <br>Cause: Not connected to the network. <br> Solutions: Please check if you can access the Internet properly.  




##### [UtilitiesNetworkToolEngineDenied](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesNetworkToolEngineDenied-constant.md) const int



Description: The server side ends the network speed test. <br>Cause: Network speed test time is too long. <br> Solutions: Please stop network speed test in 3 minutes.  




##### [UtilitiesNetworkToolInnerError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesNetworkToolInnerError-constant.md) const int



Description: Network speed test internal error. <br>Cause: Internal error. <br> Solutions: Please contact ZEGO technical support.  




##### [UtilitiesNetworkToolRtpTimeoutError](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesNetworkToolRtpTimeoutError-constant.md) const int



Description: RTP timeout. <br>Cause: Not connected to the network. <br> Solutions: Please check if you can access the Internet properly.  




##### [UtilitiesNetworkToolStoppedByPlayingStream](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesNetworkToolStoppedByPlayingStream-constant.md) const int



Description: Network speed test stopped. <br>Cause: Network speed test not stopped before playing stream. <br> Solutions: Please stop network speed test(stopNetworkSpeedTest) before playing stream.  




##### [UtilitiesNetworkToolStoppedByPublishingStream](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesNetworkToolStoppedByPublishingStream-constant.md) const int



Description: Network speed test stopped. <br>Cause: Network speed test not stopped before publishing stream. <br> Solutions: Please stop network speed test(stopNetworkSpeedTest) before publishing stream.  




##### [UtilitiesPerformanceMonitorIntervalInvalid](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesPerformanceMonitorIntervalInvalid-constant.md) const int



Description: Invalid system performance monitoring interval. <br>Cause: The set system performance monitoring interval is out of range. <br> Solutions: Please check if the system performance monitoring interval is out of range or not, valid range is <code>1000, 10000</code>.  




##### [UtilitiesStopByLoginRoom](../zego_uikit_prebuilt_live_audio_room/ZegoErrorCode/UtilitiesStopByLoginRoom-constant.md) const int



Description: Login to the room causes the network test to stop. <br>Cause: Already logged in to the room. <br>Solutions: Since the network test will take up bandwidth, please do it before logging in to the room.  









