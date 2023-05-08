


# ZegoUIKit class














**Mixed in types**

- [ZegoAudioVideoService](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService-mixin.md)
- [ZegoRoomService](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService-mixin.md)
- [ZegoUserService](../zego_uikit_prebuilt_live_audio_room/ZegoUserService-mixin.md)
- [ZegoMessageService](../zego_uikit_prebuilt_live_audio_room/ZegoMessageService-mixin.md)
- [ZegoCustomCommandService](../zego_uikit_prebuilt_live_audio_room/ZegoCustomCommandService-mixin.md)
- [ZegoDeviceService](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceService-mixin.md)
- [ZegoEffectService](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService-mixin.md)
- [ZegoPluginService](../zego_uikit_prebuilt_live_audio_room/ZegoPluginService-mixin.md)
- [ZegoLoggerService](../zego_uikit_prebuilt_live_audio_room/ZegoLoggerService-mixin.md)






## Constructors

[ZegoUIKit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit/ZegoUIKit.md) ()

   _factory_


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [clearLogs](../zego_uikit_prebuilt_live_audio_room/ZegoLoggerService/clearLogs.md)() Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [enableBeauty](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/enableBeauty.md)(bool isOn) Future&lt;void>



enable beauty  
_<span class="feature">inherited</span>_



##### [enableVideoMirroring](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/enableVideoMirroring.md)(bool isVideoMirror) void



set video mirror mode  
_<span class="feature">inherited</span>_



##### [getAllUsers](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getAllUsers.md)() List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>



get all users, include local user and remote users  
_<span class="feature">inherited</span>_



##### [getAudioOutputDeviceNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getAudioOutputDeviceNotifier.md)(String userID) ValueNotifier&lt;[ZegoAudioRoute](../zego_uikit_prebuilt_live_audio_room/ZegoAudioRoute.md)>



get audio output device notifier  
_<span class="feature">inherited</span>_



##### [getAudioVideoList](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getAudioVideoList.md)() List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>



get audio video list  
_<span class="feature">inherited</span>_



##### [getAudioVideoListStream](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getAudioVideoListStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



  
_<span class="feature">inherited</span>_



##### [getAudioVideoViewNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getAudioVideoViewNotifier.md)(String? userID, {bool isMainStream = true}) ValueNotifier&lt;Widget?>



get audio video view notifier  
_<span class="feature">inherited</span>_



##### [getBeautyValue](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/getBeautyValue.md)() [ZegoEffectsBeautyParam](../zego_uikit_prebuilt_live_audio_room/ZegoEffectsBeautyParam-class.md)



get beauty value  
_<span class="feature">inherited</span>_



##### [getCameraStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getCameraStateNotifier.md)(String userID) ValueNotifier&lt;bool>



get camera state notifier  
_<span class="feature">inherited</span>_



##### [getInRoomCommandReceivedStream](../zego_uikit_prebuilt_live_audio_room/ZegoCustomCommandService/getInRoomCommandReceivedStream.md)() Stream&lt;[ZegoInRoomCommandReceivedData](../zego_uikit_prebuilt_live_audio_room/ZegoInRoomCommandReceivedData-class.md)>



get in-room command received notifier  
_<span class="feature">inherited</span>_



##### [getInRoomMessageListStream](../zego_uikit_prebuilt_live_audio_room/ZegoMessageService/getInRoomMessageListStream.md)() Stream&lt;List&lt;[ZegoInRoomMessage](../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md)>>



get in-room messages notifier  
_<span class="feature">inherited</span>_



##### [getInRoomMessages](../zego_uikit_prebuilt_live_audio_room/ZegoMessageService/getInRoomMessages.md)() List&lt;[ZegoInRoomMessage](../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md)>



get in-room messages  
_<span class="feature">inherited</span>_



##### [getInRoomMessageStream](../zego_uikit_prebuilt_live_audio_room/ZegoMessageService/getInRoomMessageStream.md)() Stream&lt;[ZegoInRoomMessage](../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md)>



get in-room messages one-by-one notifier  
_<span class="feature">inherited</span>_



##### [getInRoomUserAttributesNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getInRoomUserAttributesNotifier.md)(String userID) ValueNotifier&lt;ZegoUIKitUserAttributes>



get notifier of in-room user attributes  
_<span class="feature">inherited</span>_



##### [getLocalUser](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getLocalUser.md)() [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)



get local user  
_<span class="feature">inherited</span>_



##### [getMeRemovedFromRoomStream](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getMeRemovedFromRoomStream.md)() Stream&lt;String>



get kicked out notifier  
_<span class="feature">inherited</span>_



##### [getMicrophoneStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMicrophoneStateNotifier.md)(String userID) ValueNotifier&lt;bool>



get microphone state notifier  
_<span class="feature">inherited</span>_



##### [getMixAudioVideoCameraStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMixAudioVideoCameraStateNotifier.md)(String mixerID, String userID) ValueNotifier&lt;bool>



  
_<span class="feature">inherited</span>_



##### [getMixAudioVideoLoadedNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMixAudioVideoLoadedNotifier.md)(String mixerID) ValueNotifier&lt;bool>



  
_<span class="feature">inherited</span>_



##### [getMixAudioVideoMicrophoneStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMixAudioVideoMicrophoneStateNotifier.md)(String mixerID, String userID) ValueNotifier&lt;bool>



  
_<span class="feature">inherited</span>_



##### [getMixAudioVideoViewNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMixAudioVideoViewNotifier.md)(String mixerID) ValueNotifier&lt;Widget?>



  
_<span class="feature">inherited</span>_



##### [getNetworkModeStream](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getNetworkModeStream.md)() Stream&lt;[ZegoNetworkMode](../zego_uikit_prebuilt_live_audio_room/ZegoNetworkMode.md)>



get network state notifier  
_<span class="feature">inherited</span>_



##### [getPlugin](../zego_uikit_prebuilt_live_audio_room/ZegoPluginService/getPlugin.md)([ZegoUIKitPluginType](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPluginType.md) type) [IZegoUIKitPlugin](../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin-mixin.md)?



get plugin object  
_<span class="feature">inherited</span>_



##### [getReceiveSEIStream](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getReceiveSEIStream.md)() Stream&lt;[ZegoUIKitReceiveSEIEvent](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitReceiveSEIEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRemoteUsers](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getRemoteUsers.md)() List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>



get remote users, not include local user  
_<span class="feature">inherited</span>_



##### [getRoom](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoom.md)() [ZegoUIKitRoom](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitRoom-class.md)



get room object  
_<span class="feature">inherited</span>_



##### [getRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoomProperties.md)() Map&lt;String, [RoomProperty](../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)>



get room properties  
_<span class="feature">inherited</span>_



##### [getRoomPropertiesStream](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoomPropertiesStream.md)() Stream&lt;Map&lt;String, [RoomProperty](../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)>>



only notify the properties which changed
you can get full properties by getRoomProperties() function  
_<span class="feature">inherited</span>_



##### [getRoomPropertyStream](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoomPropertyStream.md)() Stream&lt;[RoomProperty](../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)>



only notify the property which changed
you can get full properties by getRoomProperties() function  
_<span class="feature">inherited</span>_



##### [getRoomStateStream](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoomStateStream.md)() ValueNotifier&lt;[ZegoUIKitRoomState](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitRoomState-class.md)>



get room state notifier  
_<span class="feature">inherited</span>_



##### [getScreenSharingList](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getScreenSharingList.md)() List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>



get screen sharing list  
_<span class="feature">inherited</span>_



##### [getScreenSharingListStream](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getScreenSharingListStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



  
_<span class="feature">inherited</span>_



##### [getScreenSharingStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getScreenSharingStateNotifier.md)() ValueNotifier&lt;bool>



get screen share notifier  
_<span class="feature">inherited</span>_



##### [getSignalingPlugin](../zego_uikit_prebuilt_live_audio_room/ZegoPluginService/getSignalingPlugin.md)() [ZegoUIKitSignalingPluginImpl](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl-class.md)



signal plugin  
_<span class="feature">inherited</span>_



##### [getSoundLevelStream](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getSoundLevelStream.md)(String userID) Stream&lt;double>



get sound level notifier  
_<span class="feature">inherited</span>_



##### [getTurnOnYourCameraRequestStream](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceService/getTurnOnYourCameraRequestStream.md)() Stream&lt;String>



protocol: String is 'operator'  
_<span class="feature">inherited</span>_



##### [getTurnOnYourMicrophoneRequestStream](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceService/getTurnOnYourMicrophoneRequestStream.md)() Stream&lt;String>



protocol: String is 'operator'  
_<span class="feature">inherited</span>_



##### [getUseFrontFacingCameraStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getUseFrontFacingCameraStateNotifier.md)(String userID) ValueNotifier&lt;bool>



get front facing camera switch notifier  
_<span class="feature">inherited</span>_



##### [getUser](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getUser.md)(String userID) [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)



get user by user id  
_<span class="feature">inherited</span>_



##### [getUserJoinStream](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getUserJoinStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



get user join notifier  
_<span class="feature">inherited</span>_



##### [getUserLeaveStream](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getUserLeaveStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



get user leave notifier  
_<span class="feature">inherited</span>_



##### [getUserListStream](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getUserListStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



get user list notifier  
_<span class="feature">inherited</span>_



##### [getVideoSizeNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getVideoSizeNotifier.md)(String userID) ValueNotifier&lt;Size>



get video size notifier  
_<span class="feature">inherited</span>_



##### [getZegoUIKitVersion](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit/getZegoUIKitVersion.md)() Future&lt;String>



version  




##### [init](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit/init.md)({required int appID, String appSign = '', [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) scenario = ZegoScenario.Default}) Future&lt;void>



init  




##### [initLog](../zego_uikit_prebuilt_live_audio_room/ZegoLoggerService/initLog.md)({String folderName = 'zego_prebuilt'}) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [installPlugins](../zego_uikit_prebuilt_live_audio_room/ZegoPluginService/installPlugins.md)(List&lt;[IZegoUIKitPlugin](../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin-mixin.md)> plugins) void



install plugins  
_<span class="feature">inherited</span>_



##### [joinRoom](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/joinRoom.md)(String roomID, {String token = '', bool markAsLargeRoom = false}) Future&lt;[ZegoRoomLoginResult](../zego_uikit_prebuilt_live_audio_room/ZegoRoomLoginResult-class.md)>



join room  
_<span class="feature">inherited</span>_



##### [leaveRoom](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/leaveRoom.md)() Future&lt;[ZegoRoomLogoutResult](../zego_uikit_prebuilt_live_audio_room/ZegoRoomLogoutResult-class.md)>



leave room  
_<span class="feature">inherited</span>_



##### [login](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/login.md)(String id, String name) void



login  
_<span class="feature">inherited</span>_



##### [logout](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/logout.md)() void



logout  
_<span class="feature">inherited</span>_



##### [muteAudio](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/muteAudio.md)(String userID, bool mute) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [muteUserAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/muteUserAudioVideo.md)(String userID, bool mute) void



  
_<span class="feature">inherited</span>_



##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [removeUserFromRoom](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/removeUserFromRoom.md)(List&lt;String> userIDs) Future&lt;bool>



remove user from room, kick out  
_<span class="feature">inherited</span>_



##### [resendInRoomMessage](../zego_uikit_prebuilt_live_audio_room/ZegoMessageService/resendInRoomMessage.md)([ZegoInRoomMessage](../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md) message) void



re-send in-room message  
_<span class="feature">inherited</span>_



##### [resetBeautyEffect](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/resetBeautyEffect.md)() Future&lt;void>



reset beauty effect  
_<span class="feature">inherited</span>_



##### [resetSoundEffect](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/resetSoundEffect.md)() Future&lt;void>



reset sound effect  
_<span class="feature">inherited</span>_



##### [sendInRoomCommand](../zego_uikit_prebuilt_live_audio_room/ZegoCustomCommandService/sendInRoomCommand.md)(String command, List&lt;String> toUserIDs) Future&lt;bool>



<code>toUserIDs</code> send to everyone if empty  
_<span class="feature">inherited</span>_



##### [sendInRoomMessage](../zego_uikit_prebuilt_live_audio_room/ZegoMessageService/sendInRoomMessage.md)(String message) void



send in-room message  
_<span class="feature">inherited</span>_



##### [setAudioOutputToSpeaker](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/setAudioOutputToSpeaker.md)(bool isSpeaker) void



set audio output to speaker  
_<span class="feature">inherited</span>_



##### [setAudioVideoResourceMode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/setAudioVideoResourceMode.md)([ZegoAudioVideoResourceMode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoResourceMode.md) mode) void



  
_<span class="feature">inherited</span>_



##### [setBeautifyValue](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/setBeautifyValue.md)(int value, [BeautyEffectType](../zego_uikit_prebuilt_live_audio_room/BeautyEffectType.md) type) void



Set the intensity of the specific face beautify feature
Description: After the face beautify feature is enabled, you can specify the parameters to set the intensity of the specific feature as needed.  
_<span class="feature">inherited</span>_



##### [setReverbType](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/setReverbType.md)([ZegoReverbPreset](../zego_uikit_prebuilt_live_audio_room/ZegoReverbPreset.md) reverbPreset) void



Set reverb
Description: This method can be used to use the reverb effect in the room.  
_<span class="feature">inherited</span>_



##### [setRoomProperty](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/setRoomProperty.md)(String key, String value) Future&lt;bool>



update one room property  
_<span class="feature">inherited</span>_



##### [setVoiceChangerType](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/setVoiceChangerType.md)([ZegoVoiceChangerPreset](../zego_uikit_prebuilt_live_audio_room/ZegoVoiceChangerPreset.md) voicePreset) void



Set voice changing
Description: This method can be used to change the voice with voice effects.  
_<span class="feature">inherited</span>_



##### [startEffectsEnv](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/startEffectsEnv.md)() Future&lt;void>



start effects env  
_<span class="feature">inherited</span>_



##### [startMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startMixerTask.md)([ZegoMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md) task) Future&lt;[ZegoMixerStartResult](../zego_uikit_prebuilt_live_audio_room/ZegoMixerStartResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [startPlayAllAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startPlayAllAudioVideo.md)() void



start play all audio video  
_<span class="feature">inherited</span>_



##### [startPlayAnotherRoomAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startPlayAnotherRoomAudioVideo.md)(String roomID, String userID, {String userName = ''}) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [startPlayMixAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startPlayMixAudioVideo.md)(String mixerID, List&lt;String> users) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [startSharingScreen](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startSharingScreen.md)() Future&lt;void>



start schare screen  
_<span class="feature">inherited</span>_



##### [stopEffectsEnv](../zego_uikit_prebuilt_live_audio_room/ZegoEffectService/stopEffectsEnv.md)() Future&lt;void>



stop effects env  
_<span class="feature">inherited</span>_



##### [stopMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopMixerTask.md)([ZegoMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md) task) Future&lt;[ZegoMixerStopResult](../zego_uikit_prebuilt_live_audio_room/ZegoMixerStopResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [stopPlayAllAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopPlayAllAudioVideo.md)() void



stop play all audio video  
_<span class="feature">inherited</span>_



##### [stopPlayAnotherRoomAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopPlayAnotherRoomAudioVideo.md)(String userID) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [stopPlayMixAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopPlayMixAudioVideo.md)(String mixerID) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [stopSharingScreen](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopSharingScreen.md)() Future&lt;void>



stop share screen  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [turnCameraOn](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/turnCameraOn.md)(bool isOn, {String? userID}) void



turn on/off camera  
_<span class="feature">inherited</span>_



##### [turnMicrophoneOn](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/turnMicrophoneOn.md)(bool isOn, {String? userID, bool muteMode = false}) void



turn on/off microphone  
_<span class="feature">inherited</span>_



##### [uninit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit/uninit.md)() Future&lt;void>



uninit  




##### [updateAppOrientation](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/updateAppOrientation.md)(DeviceOrientation orientation) void



update app orientation  
_<span class="feature">inherited</span>_



##### [updateRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/updateRoomProperties.md)(Map&lt;String, String> properties) Future&lt;bool>



update room properties  
_<span class="feature">inherited</span>_



##### [updateTextureRendererOrientation](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/updateTextureRendererOrientation.md)(Orientation orientation) void



update texture render orientation  
_<span class="feature">inherited</span>_



##### [updateVideoViewMode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/updateVideoViewMode.md)(bool useVideoViewAspectFill) void



update video view mode  
_<span class="feature">inherited</span>_



##### [useFrontFacingCamera](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/useFrontFacingCamera.md)(bool isFrontFacing) void



local use front facing camera  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_





## Static Properties

##### [instance](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit/instance.md) &#8594; [ZegoUIKit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit-class.md)



  
_<span class="feature">final</span>_













