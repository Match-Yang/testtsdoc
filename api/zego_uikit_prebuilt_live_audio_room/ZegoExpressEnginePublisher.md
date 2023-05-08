


# ZegoExpressEnginePublisher extension
on [ZegoExpressEngine](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine-class.md)
















## Methods

##### [addPublishCdnUrl](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/addPublishCdnUrl.md)(String streamID, String targetURL) Future&lt;[ZegoPublisherUpdateCdnUrlResult](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherUpdateCdnUrlResult-class.md)>



Adds a target CDN URL to which the stream will be relayed from ZEGO RTC server.  




##### [enableH265EncodeFallback](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableH265EncodeFallback.md)(bool enable) Future&lt;void>



Whether to enable H.265 encoding to automatically downgrade to H.264 encoding.  




##### [enableHardwareEncoder](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableHardwareEncoder.md)(bool enable) Future&lt;void>



Enables or disables hardware encoding.  




##### [enablePublishDirectToCDN](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enablePublishDirectToCDN.md)(bool enable, {[ZegoCDNConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig-class.md)? config, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Whether to directly push to CDN (without going through the ZEGO RTC server), for the specified channel.  




##### [enableTrafficControl](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableTrafficControl.md)(bool enable, int property) Future&lt;void>



Enables or disables traffic control.  




##### [getAudioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/getAudioConfig.md)() Future&lt;[ZegoAudioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoAudioConfig-class.md)>



Gets the current audio configurations.  




##### [getVideoConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/getVideoConfig.md)({[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;[ZegoVideoConfig](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig-class.md)>



Gets the current video configurations (for the specified channel).  




##### [isVideoEncoderSupported](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/isVideoEncoderSupported.md)([ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) codecID, {[ZegoVideoCodecBackend](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecBackend.md)? codecBackend}) Future&lt;int>



Whether the specified video encoding type is supported.  




##### [mutePublishStreamAudio](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/mutePublishStreamAudio.md)(bool mute, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Stops or resumes sending the audio part of a stream for the specified channel.  




##### [mutePublishStreamVideo](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/mutePublishStreamVideo.md)(bool mute, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Stops or resumes sending the video part of a stream for the specified channel.  




##### [removePublishCdnUrl](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/removePublishCdnUrl.md)(String streamID, String targetURL) Future&lt;[ZegoPublisherUpdateCdnUrlResult](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherUpdateCdnUrlResult-class.md)>



Deletes the specified CDN URL, which is used for relaying streams from ZEGO RTC server to CDN.  




##### [sendAudioSideInfo](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/sendAudioSideInfo.md)(Uint8List data, double timeStampMs, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Send audio side information.  




##### [sendSEI](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/sendSEI.md)(Uint8List data, int dataLength, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sends Supplemental Enhancement Information.  




##### [setAppOrientation](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setAppOrientation.md)(DeviceOrientation orientation, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sets the video orientation (for the specified channel).  




##### [setAppOrientationMode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setAppOrientationMode.md)([ZegoOrientationMode](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md) mode) Future&lt;void>



Set the orientation mode of the video.  




##### [setAudioCaptureStereoMode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setAudioCaptureStereoMode.md)([ZegoAudioCaptureStereoMode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCaptureStereoMode.md) mode) Future&lt;void>



Set audio capture stereo mode.  




##### [setAudioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setAudioConfig.md)([ZegoAudioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoAudioConfig-class.md) config, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sets up the audio configurations for the specified publish channel.  




##### [setAudioSource](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setAudioSource.md)([ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) source, {[ZegoAudioSourceMixConfig](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceMixConfig-class.md)? config, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;int>



Set audio capture source with audio mix config.  




##### [setCapturePipelineScaleMode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setCapturePipelineScaleMode.md)([ZegoCapturePipelineScaleMode](../zego_uikit_prebuilt_live_audio_room/ZegoCapturePipelineScaleMode.md) mode) Future&lt;void>



Sets the timing of video scaling in the video capture workflow. You can choose to do video scaling right after video capture (the default value) or before encoding.  




##### [setCaptureVolume](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setCaptureVolume.md)(int volume) Future&lt;void>



Sets the audio recording volume for stream publishing.  




##### [setDummyCaptureImagePath](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setDummyCaptureImagePath.md)(String filePath, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel) Future&lt;void>



Set the path of the static picture would be published when the camera is closed.  




##### [setLowlightEnhancement](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setLowlightEnhancement.md)([ZegoLowlightEnhancementMode](../zego_uikit_prebuilt_live_audio_room/ZegoLowlightEnhancementMode.md) mode, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set low light enhancement.  




##### [setMinVideoBitrateForTrafficControl](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setMinVideoBitrateForTrafficControl.md)(int bitrate, [ZegoTrafficControlMinVideoBitrateMode](../zego_uikit_prebuilt_live_audio_room/ZegoTrafficControlMinVideoBitrateMode.md) mode, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sets the minimum video bitrate for traffic control for the specified publish channel.  




##### [setMinVideoFpsForTrafficControl](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setMinVideoFpsForTrafficControl.md)(int fps, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sets the minimum video frame rate threshold for traffic control.  




##### [setMinVideoResolutionForTrafficControl](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setMinVideoResolutionForTrafficControl.md)(int width, int height, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sets the minimum video resolution threshold for traffic control.  




##### [setPublishStreamEncryptionKey](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setPublishStreamEncryptionKey.md)(String key, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set encryption key for the publishing stream for the specified publish channel.  




##### [setPublishWatermark](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setPublishWatermark.md)({[ZegoWatermark](../zego_uikit_prebuilt_live_audio_room/ZegoWatermark-class.md)? watermark, bool? isPreviewVisible, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sets up the stream watermark before stream publishing (for the specified channel).  




##### [setSEIConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setSEIConfig.md)([ZegoSEIConfig](../zego_uikit_prebuilt_live_audio_room/ZegoSEIConfig-class.md) config) Future&lt;void>



Set the Supplemental Enhancement Information type.  




##### [setStreamAlignmentProperty](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setStreamAlignmentProperty.md)(int alignment, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel) Future&lt;void>



Enable or disable the stream mixing precision alignment function.  




##### [setStreamExtraInfo](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setStreamExtraInfo.md)(String extraInfo, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;[ZegoPublisherSetStreamExtraInfoResult](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherSetStreamExtraInfoResult-class.md)>



Sets the extra information of the stream being published for the specified publish channel.  




##### [setTrafficControlFocusOn](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setTrafficControlFocusOn.md)([ZegoTrafficControlFocusOnMode](../zego_uikit_prebuilt_live_audio_room/ZegoTrafficControlFocusOnMode.md) mode, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Set the factors of concern that trigger traffic control for the specified publish channel.  




##### [setVideoConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setVideoConfig.md)([ZegoVideoConfig](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig-class.md) config, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sets up the video configurations (for the specified channel).  




##### [setVideoMirrorMode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setVideoMirrorMode.md)([ZegoVideoMirrorMode](../zego_uikit_prebuilt_live_audio_room/ZegoVideoMirrorMode.md) mirrorMode, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sets the video mirroring mode (for the specified channel).  




##### [setVideoSource](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setVideoSource.md)([ZegoVideoSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoVideoSourceType.md) source, {int? instanceID, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;int>



Set a video capture instance as video capture source for the specified channel.  




##### [startPreview](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md)({[ZegoCanvas](../zego_uikit_prebuilt_live_audio_room/ZegoCanvas-class.md)? canvas, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Starts/Updates the local video preview (for the specified channel).  




##### [startPublishingStream](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md)(String streamID, {[ZegoPublisherConfig](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig-class.md)? config, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Starts publishing a stream. Support multi-room mode.  




##### [stopPreview](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/stopPreview.md)({[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Stops the local preview (for the specified channel).  




##### [stopPublishingStream](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/stopPublishingStream.md)({[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Stops publishing a stream (for the specified channel).  




##### [takePublishStreamSnapshot](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/takePublishStreamSnapshot.md)({[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;[ZegoPublisherTakeSnapshotResult](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherTakeSnapshotResult-class.md)>



Take a snapshot of the publishing stream for the specified publish channel.  


















