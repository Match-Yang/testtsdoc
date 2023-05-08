


# ZegoExpressEngineDevice extension
on [ZegoExpressEngine](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine-class.md)
















## Methods

##### [enableAudioCaptureDevice](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableAudioCaptureDevice.md)(bool enable) Future&lt;void>



Enables or disables the audio capture device.  




##### [enableCamera](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableCamera.md)(bool enable, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Turns on/off the camera (for the specified channel).  




##### [enableCameraAdaptiveFPS](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableCameraAdaptiveFPS.md)(bool enable, int minFPS, int maxFPS, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel) Future&lt;void>



Enable camera adaptive frame rate.  




##### [enableHeadphoneMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableHeadphoneMonitor.md)(bool enable) Future&lt;void>



Enables or disables headphone monitoring.  




##### [enableMixEnginePlayout](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableMixEnginePlayout.md)(bool enable) Future&lt;void>



Enable or disable mix SDK playout to stream publishing.  




##### [enableMixSystemPlayout](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/enableMixSystemPlayout.md)(bool enable) Future&lt;void>



Enable or disable system audio capture.  




##### [getAudioDeviceList](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceList.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType) Future&lt;List&lt;[ZegoDeviceInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md)>>



Gets a list of audio devices.  




##### [getAudioDeviceVolume](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioDeviceVolume.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID) Future&lt;int>



Get volume for the specified audio device.  




##### [getAudioRouteType](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getAudioRouteType.md)() Future&lt;[ZegoAudioRoute](../zego_uikit_prebuilt_live_audio_room/ZegoAudioRoute.md)>



get current audio route type.  




##### [getCameraMaxZoomFactor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getCameraMaxZoomFactor.md)({[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;double>



Get the maximum zoom factor of the camera.  




##### [getCurrentAudioDevice](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getCurrentAudioDevice.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType) Future&lt;[ZegoDeviceInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md)>



Get the audio device information currently in use.  




##### [getDefaultAudioDeviceID](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getDefaultAudioDeviceID.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType) Future&lt;String>



Get the device ID of the default audio device.  




##### [getDefaultVideoDeviceID](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getDefaultVideoDeviceID.md)() Future&lt;String>



Get the device ID of the default video device.  




##### [getVideoDeviceList](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getVideoDeviceList.md)() Future&lt;List&lt;[ZegoDeviceInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md)>>



Gets a list of video devices.  




##### [isAudioDeviceMuted](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/isAudioDeviceMuted.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID) Future&lt;bool>



Check if the audio device is muted.  




##### [isCameraFocusSupported](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/isCameraFocusSupported.md)({[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;bool>



Whether the camera supports focusing.  




##### [isMicrophoneMuted](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/isMicrophoneMuted.md)() Future&lt;bool>



Checks whether the microphone is muted.  




##### [isSpeakerMuted](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/isSpeakerMuted.md)() Future&lt;bool>



Checks whether the audio output speaker is muted.  




##### [muteAudioDevice](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/muteAudioDevice.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID, bool mute) Future&lt;void>



Mutes or unmutes the audio device.  




##### [muteMicrophone](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/muteMicrophone.md)(bool mute) Future&lt;void>



Mutes or unmutes the microphone.  




##### [muteSpeaker](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/muteSpeaker.md)(bool mute) Future&lt;void>



Mutes or unmutes the audio output speaker.  




##### [setAudioDeviceMode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setAudioDeviceMode.md)([ZegoAudioDeviceMode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceMode.md) deviceMode) Future&lt;void>



Set the audio device mode.  




##### [setAudioDeviceVolume](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setAudioDeviceVolume.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID, int volume) Future&lt;void>



Set volume for the specified audio device.  




##### [setAudioRouteToSpeaker](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setAudioRouteToSpeaker.md)(bool defaultToSpeaker) Future&lt;void>



Whether to use the built-in speaker to play audio.  




##### [setCameraExposureCompensation](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setCameraExposureCompensation.md)(double value, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set the camera exposure compensation value.  




##### [setCameraExposureMode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setCameraExposureMode.md)([ZegoCameraExposureMode](../zego_uikit_prebuilt_live_audio_room/ZegoCameraExposureMode.md) mode, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set the camera exposure mode.  




##### [setCameraExposurePointInPreview](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setCameraExposurePointInPreview.md)(double x, double y, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set the exposure point in the preview view.  




##### [setCameraFocusMode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setCameraFocusMode.md)([ZegoCameraFocusMode](../zego_uikit_prebuilt_live_audio_room/ZegoCameraFocusMode.md) mode, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set the camera focus mode.  




##### [setCameraFocusPointInPreview](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setCameraFocusPointInPreview.md)(double x, double y, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set the focus point in the preview view.  




##### [setCameraZoomFactor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setCameraZoomFactor.md)(double factor, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set the zoom factor of the camera. Every time the camera is restarted, the camera zoom factor will return to the initial value (1.0).  




##### [setHeadphoneMonitorVolume](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setHeadphoneMonitorVolume.md)(int volume) Future&lt;void>



Sets the headphone monitor volume.  




##### [setMixSystemPlayoutVolume](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setMixSystemPlayoutVolume.md)(int volume) Future&lt;void>



set system audio capture volume.  




##### [startAudioDeviceVolumeMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/startAudioDeviceVolumeMonitor.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID) Future&lt;void>



Turn on audio device volume monitoring.  




##### [startAudioSpectrumMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/startAudioSpectrumMonitor.md)({int? millisecond}) Future&lt;void>



Starts audio spectrum monitoring. Support setting the listening interval.  




##### [startAudioVADStableStateMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/startAudioVADStableStateMonitor.md)([ZegoAudioVADStableStateMonitorType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVADStableStateMonitorType.md) type, {int? millisecond}) Future&lt;void>



Start audio VAD stable state monitoring, and the monitoring period can be set.  




##### [startSoundLevelMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/startSoundLevelMonitor.md)({[ZegoSoundLevelConfig](../zego_uikit_prebuilt_live_audio_room/ZegoSoundLevelConfig-class.md)? config}) Future&lt;void>



Starts sound level monitoring. Support enable some advanced feature.  




##### [stopAudioDeviceVolumeMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/stopAudioDeviceVolumeMonitor.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID) Future&lt;void>



Turn off audio device volume monitoring. Only for Windows/macOS.  




##### [stopAudioSpectrumMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/stopAudioSpectrumMonitor.md)() Future&lt;void>



Stops audio spectrum monitoring.  




##### [stopAudioVADStableStateMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/stopAudioVADStableStateMonitor.md)([ZegoAudioVADStableStateMonitorType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVADStableStateMonitorType.md) type) Future&lt;void>



Stop audio VAD stable state monitoring.  




##### [stopSoundLevelMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/stopSoundLevelMonitor.md)() Future&lt;void>



Stops sound level monitoring.  




##### [useAudioDevice](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/useAudioDevice.md)([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID) Future&lt;void>



Chooses to use the specified audio device.  




##### [useAudioOutputDevice](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/useAudioOutputDevice.md)(int viewID, String deviceID) Future&lt;void>



Switch the audio output device.  




##### [useFrontCamera](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/useFrontCamera.md)(bool enable, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Switches to the front or the rear camera (for the specified channel).  




##### [useVideoDevice](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/useVideoDevice.md)(String deviceID, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Chooses to use the specified video device (for the specified channel).  


















