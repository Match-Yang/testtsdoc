


# ZegoAudioVideoService mixin















**Mixin Applications**

- [ZegoUIKit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit-class.md)



## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [enableVideoMirroring](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/enableVideoMirroring.md)(bool isVideoMirror) void



set video mirror mode  




##### [getAudioOutputDeviceNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getAudioOutputDeviceNotifier.md)(String userID) ValueNotifier&lt;[ZegoAudioRoute](../zego_uikit_prebuilt_live_audio_room/ZegoAudioRoute.md)>



get audio output device notifier  




##### [getAudioVideoList](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getAudioVideoList.md)() List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>



get audio video list  




##### [getAudioVideoListStream](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getAudioVideoListStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



  




##### [getAudioVideoViewNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getAudioVideoViewNotifier.md)(String? userID, {bool isMainStream = true}) ValueNotifier&lt;Widget?>



get audio video view notifier  




##### [getCameraStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getCameraStateNotifier.md)(String userID) ValueNotifier&lt;bool>



get camera state notifier  




##### [getMicrophoneStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMicrophoneStateNotifier.md)(String userID) ValueNotifier&lt;bool>



get microphone state notifier  




##### [getMixAudioVideoCameraStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMixAudioVideoCameraStateNotifier.md)(String mixerID, String userID) ValueNotifier&lt;bool>



  




##### [getMixAudioVideoLoadedNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMixAudioVideoLoadedNotifier.md)(String mixerID) ValueNotifier&lt;bool>



  




##### [getMixAudioVideoMicrophoneStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMixAudioVideoMicrophoneStateNotifier.md)(String mixerID, String userID) ValueNotifier&lt;bool>



  




##### [getMixAudioVideoViewNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getMixAudioVideoViewNotifier.md)(String mixerID) ValueNotifier&lt;Widget?>



  




##### [getReceiveSEIStream](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getReceiveSEIStream.md)() Stream&lt;[ZegoUIKitReceiveSEIEvent](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitReceiveSEIEvent-class.md)>



  




##### [getScreenSharingList](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getScreenSharingList.md)() List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>



get screen sharing list  




##### [getScreenSharingListStream](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getScreenSharingListStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



  




##### [getScreenSharingStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getScreenSharingStateNotifier.md)() ValueNotifier&lt;bool>



get screen share notifier  




##### [getSoundLevelStream](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getSoundLevelStream.md)(String userID) Stream&lt;double>



get sound level notifier  




##### [getUseFrontFacingCameraStateNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getUseFrontFacingCameraStateNotifier.md)(String userID) ValueNotifier&lt;bool>



get front facing camera switch notifier  




##### [getVideoSizeNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/getVideoSizeNotifier.md)(String userID) ValueNotifier&lt;Size>



get video size notifier  




##### [muteAudio](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/muteAudio.md)(String userID, bool mute) Future&lt;void>



  




##### [muteUserAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/muteUserAudioVideo.md)(String userID, bool mute) void



  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [setAudioOutputToSpeaker](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/setAudioOutputToSpeaker.md)(bool isSpeaker) void



set audio output to speaker  




##### [setAudioVideoResourceMode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/setAudioVideoResourceMode.md)([ZegoAudioVideoResourceMode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoResourceMode.md) mode) void



  




##### [startMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startMixerTask.md)([ZegoMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md) task) Future&lt;[ZegoMixerStartResult](../zego_uikit_prebuilt_live_audio_room/ZegoMixerStartResult-class.md)>



  




##### [startPlayAllAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startPlayAllAudioVideo.md)() void



start play all audio video  




##### [startPlayAnotherRoomAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startPlayAnotherRoomAudioVideo.md)(String roomID, String userID, {String userName = ''}) Future&lt;void>



  




##### [startPlayMixAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startPlayMixAudioVideo.md)(String mixerID, List&lt;String> users) Future&lt;void>



  




##### [startSharingScreen](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/startSharingScreen.md)() Future&lt;void>



start schare screen  




##### [stopMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopMixerTask.md)([ZegoMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask-class.md) task) Future&lt;[ZegoMixerStopResult](../zego_uikit_prebuilt_live_audio_room/ZegoMixerStopResult-class.md)>



  




##### [stopPlayAllAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopPlayAllAudioVideo.md)() void



stop play all audio video  




##### [stopPlayAnotherRoomAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopPlayAnotherRoomAudioVideo.md)(String userID) Future&lt;void>



  




##### [stopPlayMixAudioVideo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopPlayMixAudioVideo.md)(String mixerID) Future&lt;void>



  




##### [stopSharingScreen](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/stopSharingScreen.md)() Future&lt;void>



stop share screen  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [turnCameraOn](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/turnCameraOn.md)(bool isOn, {String? userID}) void



turn on/off camera  




##### [turnMicrophoneOn](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/turnMicrophoneOn.md)(bool isOn, {String? userID, bool muteMode = false}) void



turn on/off microphone  




##### [updateAppOrientation](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/updateAppOrientation.md)(DeviceOrientation orientation) void



update app orientation  




##### [updateTextureRendererOrientation](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/updateTextureRendererOrientation.md)(Orientation orientation) void



update texture render orientation  




##### [updateVideoViewMode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/updateVideoViewMode.md)(bool useVideoViewAspectFill) void



update video view mode  




##### [useFrontFacingCamera](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/useFrontFacingCamera.md)(bool isFrontFacing) void



local use front facing camera  






## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVideoService/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















