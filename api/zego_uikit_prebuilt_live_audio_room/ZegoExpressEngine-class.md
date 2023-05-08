


# ZegoExpressEngine class
















**Available Extensions**

- [ZegoExpressAssetsUtils](../zego_uikit_prebuilt_live_audio_room/ZegoExpressAssetsUtils.md)
- [ZegoExpressCanvasViewUtils](../zego_uikit_prebuilt_live_audio_room/ZegoExpressCanvasViewUtils.md)
- [ZegoExpressEngineAudioEffectPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineAudioEffectPlayer.md)
- [ZegoExpressEngineCopyrightedMusic](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCopyrightedMusic.md)
- [ZegoExpressEngineCustomAudioIO](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO.md)
- [ZegoExpressEngineCustomVideoIO](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomVideoIO.md)
- [ZegoExpressEngineDeprecatedApi](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDeprecatedApi.md)
- [ZegoExpressEngineDevice](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice.md)
- [ZegoExpressEngineIM](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM.md)
- [ZegoExpressEngineMediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMediaPlayer.md)
- [ZegoExpressEngineMixer](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineMixer.md)
- [ZegoExpressEnginePlayer](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer.md)
- [ZegoExpressEnginePreprocess](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePreprocess.md)
- [ZegoExpressEnginePublisher](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher.md)
- [ZegoExpressEngineRangeAudio](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRangeAudio.md)
- [ZegoExpressEngineRecord](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRecord.md)
- [ZegoExpressEngineRoom](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom.md)
- [ZegoExpressEngineScreenCapture](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineScreenCapture.md)
- [ZegoExpressEngineUtilities](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineUtilities.md)





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [callExperimentalAPI](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/callExperimentalAPI.md)(String params) Future&lt;String>



Call the experimental API.  




##### [enableDebugAssistant](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/enableDebugAssistant.md)(bool enable) Future&lt;void>



Enable the debug assistant. Note, do not enable this feature in the online version! Use only during development phase!  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [setRoomScenario](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setRoomScenario.md)([ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) scenario) Future&lt;void>



Set room scenario.  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [uploadLog](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/uploadLog.md)() Future&lt;void>



Uploads logs to the ZEGO server.  






## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_





## Static Properties

##### [instance](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/instance.md) &#8594; [ZegoExpressEngine](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine-class.md)



Engine singleton instance  
_<span class="feature">final</span>_



##### [onAlignedAudioAuxData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAlignedAudioAuxData.md) &#8596; (void Function(Uint8List data, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)?)



Aligned audio aux frames callback.  
_<span class="feature">read / write</span>_



##### [onApiCalledResult](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onApiCalledResult.md) &#8596; (void Function(int errorCode, String funcName, String info)?)



Method execution result callback  
_<span class="feature">read / write</span>_



##### [onAudioDeviceStateChanged](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAudioDeviceStateChanged.md) &#8596; (void Function([ZegoUpdateType](../zego_uikit_prebuilt_live_audio_room/ZegoUpdateType.md) updateType, [ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, [ZegoDeviceInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md) deviceInfo)?)



The callback triggered when there is a change to audio devices (i.e. new device added or existing device deleted).  
_<span class="feature">read / write</span>_



##### [onAudioDeviceVolumeChanged](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAudioDeviceVolumeChanged.md) &#8596; (void Function([ZegoAudioDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioDeviceType.md) deviceType, String deviceID, int volume)?)



The callback triggered when there is a change of the volume for the audio devices.  
_<span class="feature">read / write</span>_



##### [onAudioEffectPlayStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAudioEffectPlayStateUpdate.md) &#8596; (void Function([ZegoAudioEffectPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer-class.md) audioEffectPlayer, int audioEffectID, [ZegoAudioEffectPlayState](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayState.md) state, int errorCode)?)



Audio effect playback state callback.  
_<span class="feature">read / write</span>_



##### [onAudioRouteChange](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAudioRouteChange.md) &#8596; (void Function([ZegoAudioRoute](../zego_uikit_prebuilt_live_audio_room/ZegoAudioRoute.md) audioRoute)?)



Callback for device's audio route changed.  
_<span class="feature">read / write</span>_



##### [onAudioVADStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAudioVADStateUpdate.md) &#8596; (void Function([ZegoAudioVADStableStateMonitorType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVADStableStateMonitorType.md) type, [ZegoAudioVADType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioVADType.md) state)?)



Callback for audio VAD  stable state update.  
_<span class="feature">read / write</span>_



##### [onAutoMixerSoundLevelUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onAutoMixerSoundLevelUpdate.md) &#8596; (void Function(Map&lt;String, double> soundLevels)?)



The callback triggered when the sound level of any input stream changes in the auto stream mixing process.  
_<span class="feature">read / write</span>_



##### [onCapturedAudioData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedAudioData.md) &#8596; (void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)?)



The callback for obtaining the audio data captured by the local microphone.  
_<span class="feature">read / write</span>_



##### [onCapturedAudioSpectrumUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedAudioSpectrumUpdate.md) &#8596; (void Function(List&lt;double> audioSpectrum)?)



The local captured audio spectrum callback.  
_<span class="feature">read / write</span>_



##### [onCapturedDataRecordProgressUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedDataRecordProgressUpdate.md) &#8596; (void Function([ZegoDataRecordProgress](../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordProgress-class.md) progress, [ZegoDataRecordConfig](../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordConfig-class.md) config, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?)



The callback to report the current recording progress.  
_<span class="feature">read / write</span>_



##### [onCapturedDataRecordStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedDataRecordStateUpdate.md) &#8596; (void Function([ZegoDataRecordState](../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordState.md) state, int errorCode, [ZegoDataRecordConfig](../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordConfig-class.md) config, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?)



The callback triggered when the state of data recording (to a file) changes.  
_<span class="feature">read / write</span>_



##### [onCapturedSoundLevelInfoUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedSoundLevelInfoUpdate.md) &#8596; (void Function([ZegoSoundLevelInfo](../zego_uikit_prebuilt_live_audio_room/ZegoSoundLevelInfo-class.md) soundLevelInfo)?)



The local captured audio sound level callback.  
_<span class="feature">read / write</span>_



##### [onCapturedSoundLevelUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCapturedSoundLevelUpdate.md) &#8596; (void Function(double soundLevel)?)



The local captured audio sound level callback.  
_<span class="feature">read / write</span>_



##### [onCurrentPitchValueUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onCurrentPitchValueUpdate.md) &#8596; (void Function([ZegoCopyrightedMusic](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic-class.md) copyrightedMusic, String resourceID, int currentDuration, int pitchValue)?)



Real-time pitch line callback.  
_<span class="feature">read / write</span>_



##### [onDebugError](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onDebugError.md) &#8596; (void Function(int errorCode, String funcName, String info)?)



The callback for obtaining debugging error information.  
_<span class="feature">read / write</span>_



##### [onDownloadProgressUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onDownloadProgressUpdate.md) &#8596; (void Function([ZegoCopyrightedMusic](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic-class.md) copyrightedMusic, String resourceID, double progressRate)?)



Callback for download song or accompaniment progress rate.  
_<span class="feature">read / write</span>_



##### [onEngineStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onEngineStateUpdate.md) &#8596; (void Function([ZegoEngineState](../zego_uikit_prebuilt_live_audio_room/ZegoEngineState.md) state)?)



The callback triggered when the audio/video engine state changes.  
_<span class="feature">read / write</span>_



##### [onExceptionOccurred](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onExceptionOccurred.md) &#8596; (void Function([ZegoScreenCaptureSource](../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSource-class.md) source, [ZegoScreenCaptureSourceExceptionType](../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSourceExceptionType.md) exceptionType)?)



The callback triggered when a screen capture source exception occurred  
_<span class="feature">read / write</span>_



##### [onIMRecvBarrageMessage](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBarrageMessage.md) &#8596; (void Function(String roomID, List&lt;[ZegoBarrageMessageInfo](../zego_uikit_prebuilt_live_audio_room/ZegoBarrageMessageInfo-class.md)> messageList)?)



The callback triggered when Barrage Messages are received.  
_<span class="feature">read / write</span>_



##### [onIMRecvBroadcastMessage](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvBroadcastMessage.md) &#8596; (void Function(String roomID, List&lt;[ZegoBroadcastMessageInfo](../zego_uikit_prebuilt_live_audio_room/ZegoBroadcastMessageInfo-class.md)> messageList)?)



The callback triggered when Broadcast Messages are received.  
_<span class="feature">read / write</span>_



##### [onIMRecvCustomCommand](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onIMRecvCustomCommand.md) &#8596; (void Function(String roomID, [ZegoUser](../zego_uikit_prebuilt_live_audio_room/ZegoUser-class.md) fromUser, String command)?)



The callback triggered when a Custom Command is received.  
_<span class="feature">read / write</span>_



##### [onLocalDeviceExceptionOccurred](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onLocalDeviceExceptionOccurred.md) &#8596; (void Function([ZegoDeviceExceptionType](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceExceptionType.md) exceptionType, [ZegoDeviceType](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceType.md) deviceType, String deviceID)?)



The callback triggered when a local device exception occurred.  
_<span class="feature">read / write</span>_



##### [onMediaPlayerFrequencySpectrumUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMediaPlayerFrequencySpectrumUpdate.md) &#8596; (void Function([ZegoMediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, List&lt;double> spectrumList)?)



The callback of frequency spectrum update.  
_<span class="feature">read / write</span>_



##### [onMediaPlayerNetworkEvent](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMediaPlayerNetworkEvent.md) &#8596; (void Function([ZegoMediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, [ZegoMediaPlayerNetworkEvent](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerNetworkEvent.md) networkEvent)?)



The callback triggered when the network status of the media player changes.  
_<span class="feature">read / write</span>_



##### [onMediaPlayerPlayingProgress](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMediaPlayerPlayingProgress.md) &#8596; (void Function([ZegoMediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, int millisecond)?)



The callback to report the current playback progress of the media player.  
_<span class="feature">read / write</span>_



##### [onMediaPlayerRecvSEI](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMediaPlayerRecvSEI.md) &#8596; (void Function([ZegoMediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, Uint8List data)?)



The callback triggered when the media player got media side info.  
_<span class="feature">read / write</span>_



##### [onMediaPlayerSoundLevelUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMediaPlayerSoundLevelUpdate.md) &#8596; (void Function([ZegoMediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, double soundLevel)?)



The callback of sound level update.  
_<span class="feature">read / write</span>_



##### [onMediaPlayerStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMediaPlayerStateUpdate.md) &#8596; (void Function([ZegoMediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer-class.md) mediaPlayer, [ZegoMediaPlayerState](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerState.md) state, int errorCode)?)



MediaPlayer playback status callback.  
_<span class="feature">read / write</span>_



##### [onMixedAudioData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMixedAudioData.md) &#8596; (void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)?)



The callback for obtaining the mixed audio data. Such mixed auido data are generated by the SDK by mixing the audio data of all the remote playing streams and the auido data captured locally.  
_<span class="feature">read / write</span>_



##### [onMixerRelayCDNStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMixerRelayCDNStateUpdate.md) &#8596; (void Function(String taskID, List&lt;[ZegoStreamRelayCDNInfo](../zego_uikit_prebuilt_live_audio_room/ZegoStreamRelayCDNInfo-class.md)> infoList)?)



The callback triggered when the state of relayed streaming of the mixed stream to CDN changes.  
_<span class="feature">read / write</span>_



##### [onMixerSoundLevelUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onMixerSoundLevelUpdate.md) &#8596; (void Function(Map&lt;int, double> soundLevels)?)



The callback triggered when the sound level of any input stream changes in the stream mixing process.  
_<span class="feature">read / write</span>_



##### [onNetworkModeChanged](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onNetworkModeChanged.md) &#8596; (void Function([ZegoNetworkMode](../zego_uikit_prebuilt_live_audio_room/ZegoNetworkMode.md) mode)?)



Network mode changed callback.  
_<span class="feature">read / write</span>_



##### [onNetworkQuality](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onNetworkQuality.md) &#8596; (void Function(String userID, [ZegoStreamQualityLevel](../zego_uikit_prebuilt_live_audio_room/ZegoStreamQualityLevel.md) upstreamQuality, [ZegoStreamQualityLevel](../zego_uikit_prebuilt_live_audio_room/ZegoStreamQualityLevel.md) downstreamQuality)?)



The network quality callback of users who are publishing in the room.  
_<span class="feature">read / write</span>_



##### [onNetworkSpeedTestError](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onNetworkSpeedTestError.md) &#8596; (void Function(int errorCode, [ZegoNetworkSpeedTestType](../zego_uikit_prebuilt_live_audio_room/ZegoNetworkSpeedTestType.md) type)?)



Network speed test error callback.  
_<span class="feature">read / write</span>_



##### [onNetworkSpeedTestQualityUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onNetworkSpeedTestQualityUpdate.md) &#8596; (void Function([ZegoNetworkSpeedTestQuality](../zego_uikit_prebuilt_live_audio_room/ZegoNetworkSpeedTestQuality-class.md) quality, [ZegoNetworkSpeedTestType](../zego_uikit_prebuilt_live_audio_room/ZegoNetworkSpeedTestType.md) type)?)



Network speed test quality callback.  
_<span class="feature">read / write</span>_



##### [onNetworkTimeSynchronized](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onNetworkTimeSynchronized.md) &#8596; (void Function()?)



Successful callback of network time synchronization..  
_<span class="feature">read / write</span>_



##### [onPerformanceStatusUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPerformanceStatusUpdate.md) &#8596; (void Function([ZegoPerformanceStatus](../zego_uikit_prebuilt_live_audio_room/ZegoPerformanceStatus-class.md) status)?)



System performance monitoring callback.  
_<span class="feature">read / write</span>_



##### [onPlaybackAudioData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlaybackAudioData.md) &#8596; (void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param)?)



The callback for obtaining the audio data of all the streams playback by SDK.  
_<span class="feature">read / write</span>_



##### [onPlayerAudioData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerAudioData.md) &#8596; (void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, String streamID)?)



The callback for obtaining the audio data of each stream.  
_<span class="feature">read / write</span>_



##### [onPlayerLowFpsWarning](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerLowFpsWarning.md) &#8596; (void Function([ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) codecID, String streamID)?)



Playing stream low frame rate warning.  
_<span class="feature">read / write</span>_



##### [onPlayerMediaEvent](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerMediaEvent.md) &#8596; (void Function(String streamID, [ZegoPlayerMediaEvent](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerMediaEvent.md) event)?)



The callback triggered when a media event occurs during streaming playing.  
_<span class="feature">read / write</span>_



##### [onPlayerQualityUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerQualityUpdate.md) &#8596; (void Function(String streamID, [ZegoPlayStreamQuality](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality-class.md) quality)?)



Callback for current stream playing quality.  
_<span class="feature">read / write</span>_



##### [onPlayerRecvAudioFirstFrame](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRecvAudioFirstFrame.md) &#8596; (void Function(String streamID)?)



The callback triggered when the first audio frame is received.  
_<span class="feature">read / write</span>_



##### [onPlayerRecvAudioSideInfo](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRecvAudioSideInfo.md) &#8596; (void Function(String streamID, Uint8List data)?)



Receive the audio side information content of the remote stream.  
_<span class="feature">read / write</span>_



##### [onPlayerRecvSEI](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRecvSEI.md) &#8596; (void Function(String streamID, Uint8List data)?)



The callback triggered when Supplemental Enhancement Information is received.  
_<span class="feature">read / write</span>_



##### [onPlayerRecvVideoFirstFrame](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRecvVideoFirstFrame.md) &#8596; (void Function(String streamID)?)



The callback triggered when the first video frame is received.  
_<span class="feature">read / write</span>_



##### [onPlayerRenderCameraVideoFirstFrame](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRenderCameraVideoFirstFrame.md) &#8596; (void Function(String streamID)?)



Calls back when the stream playing end renders the first frame of the video from the remote camera.  
_<span class="feature">read / write</span>_



##### [onPlayerRenderVideoFirstFrame](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerRenderVideoFirstFrame.md) &#8596; (void Function(String streamID)?)



The callback triggered when the first video frame is rendered.  
_<span class="feature">read / write</span>_



##### [onPlayerStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerStateUpdate.md) &#8596; (void Function(String streamID, [ZegoPlayerState](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md) state, int errorCode, Map&lt;String, dynamic> extendedData)?)



The callback triggered when the state of stream playing changes.  
_<span class="feature">read / write</span>_



##### [onPlayerStreamEvent](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerStreamEvent.md) &#8596; (void Function([ZegoStreamEvent](../zego_uikit_prebuilt_live_audio_room/ZegoStreamEvent.md) eventID, String streamID, String extraInfo)?)



The callback triggered when playing stream.  
_<span class="feature">read / write</span>_



##### [onPlayerVideoSizeChanged](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerVideoSizeChanged.md) &#8596; (void Function(String streamID, int width, int height)?)



The callback triggered when the stream playback resolution changes.  
_<span class="feature">read / write</span>_



##### [onPlayerVideoSuperResolutionUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPlayerVideoSuperResolutionUpdate.md) &#8596; (void Function(String streamID, [ZegoSuperResolutionState](../zego_uikit_prebuilt_live_audio_room/ZegoSuperResolutionState.md) state, int errorCode)?)



Playing stream video super resolution enabled state changes.  
_<span class="feature">read / write</span>_



##### [onProcessCapturedAudioData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onProcessCapturedAudioData.md) &#8596; (void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, double timestamp)?)



Custom audio processing local captured PCM audio frame callback.  
_<span class="feature">read / write</span>_



##### [onProcessCapturedAudioDataAfterUsedHeadphoneMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onProcessCapturedAudioDataAfterUsedHeadphoneMonitor.md) &#8596; (void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, double timestamp)?)



Custom audio processing local captured PCM audio frame callback after used headphone monitor.  
_<span class="feature">read / write</span>_



##### [onProcessPlaybackAudioData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onProcessPlaybackAudioData.md) &#8596; (void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, double timestamp)?)



Custom audio processing SDK playback PCM audio frame callback.  
_<span class="feature">read / write</span>_



##### [onProcessRemoteAudioData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onProcessRemoteAudioData.md) &#8596; (void Function(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, String streamID, double timestamp)?)



Custom audio processing remote playing stream PCM audio frame callback.  
_<span class="feature">read / write</span>_



##### [onPublisherCapturedAudioFirstFrame](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherCapturedAudioFirstFrame.md) &#8596; (void Function()?)



The callback triggered when the first audio frame is captured.  
_<span class="feature">read / write</span>_



##### [onPublisherCapturedVideoFirstFrame](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherCapturedVideoFirstFrame.md) &#8596; (void Function([ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?)



The callback triggered when the first video frame is captured.  
_<span class="feature">read / write</span>_



##### [onPublisherQualityUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherQualityUpdate.md) &#8596; (void Function(String streamID, [ZegoPublishStreamQuality](../zego_uikit_prebuilt_live_audio_room/ZegoPublishStreamQuality-class.md) quality)?)



Callback for current stream publishing quality.  
_<span class="feature">read / write</span>_



##### [onPublisherRelayCDNStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherRelayCDNStateUpdate.md) &#8596; (void Function(String streamID, List&lt;[ZegoStreamRelayCDNInfo](../zego_uikit_prebuilt_live_audio_room/ZegoStreamRelayCDNInfo-class.md)> infoList)?)



The callback triggered when the state of relayed streaming to CDN changes.  
_<span class="feature">read / write</span>_



##### [onPublisherRenderVideoFirstFrame](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherRenderVideoFirstFrame.md) &#8596; (void Function([ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?)



The callback triggered when the first video frame is rendered.  
_<span class="feature">read / write</span>_



##### [onPublisherStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherStateUpdate.md) &#8596; (void Function(String streamID, [ZegoPublisherState](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md) state, int errorCode, Map&lt;String, dynamic> extendedData)?)



The callback triggered when the state of stream publishing changes.  
_<span class="feature">read / write</span>_



##### [onPublisherStreamEvent](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherStreamEvent.md) &#8596; (void Function([ZegoStreamEvent](../zego_uikit_prebuilt_live_audio_room/ZegoStreamEvent.md) eventID, String streamID, String extraInfo)?)



The callback triggered when publishing stream.  
_<span class="feature">read / write</span>_



##### [onPublisherVideoEncoderChanged](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherVideoEncoderChanged.md) &#8596; (void Function([ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) fromCodecID, [ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) toCodecID, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?)



The callback triggered when the video encoder changes in publishing stream.  
_<span class="feature">read / write</span>_



##### [onPublisherVideoSizeChanged](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPublisherVideoSizeChanged.md) &#8596; (void Function(int width, int height, [ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?)



The callback triggered when the video capture resolution changes.  
_<span class="feature">read / write</span>_



##### [onRangeAudioMicrophoneStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRangeAudioMicrophoneStateUpdate.md) &#8596; (void Function([ZegoRangeAudio](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio-class.md) rangeAudio, [ZegoRangeAudioMicrophoneState](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudioMicrophoneState.md) state, int errorCode)?)



Range audio microphone state callback.  
_<span class="feature">read / write</span>_



##### [onReceiveRealTimeSequentialData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onReceiveRealTimeSequentialData.md) &#8596; (void Function([ZegoRealTimeSequentialDataManager](../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md) manager, Uint8List data, String streamID)?)



Callback for receiving real-time sequential data.  
_<span class="feature">read / write</span>_



##### [onRecvExperimentalAPI](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRecvExperimentalAPI.md) &#8596; (void Function(String content)?)



Experimental API callback  
_<span class="feature">read / write</span>_



##### [onRemoteAudioSpectrumUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteAudioSpectrumUpdate.md) &#8596; (void Function(Map&lt;String, List&lt;double>> audioSpectrums)?)



The remote playing streams audio spectrum callback.  
_<span class="feature">read / write</span>_



##### [onRemoteCameraStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteCameraStateUpdate.md) &#8596; (void Function(String streamID, [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) state)?)



The callback triggered when the state of the remote camera changes.  
_<span class="feature">read / write</span>_



##### [onRemoteMicStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteMicStateUpdate.md) &#8596; (void Function(String streamID, [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) state)?)



The callback triggered when the state of the remote microphone changes.  
_<span class="feature">read / write</span>_



##### [onRemoteSoundLevelInfoUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteSoundLevelInfoUpdate.md) &#8596; (void Function(Map&lt;String, [ZegoSoundLevelInfo](../zego_uikit_prebuilt_live_audio_room/ZegoSoundLevelInfo-class.md)> soundLevelInfos)?)



The remote playing streams audio sound level callback.  
_<span class="feature">read / write</span>_



##### [onRemoteSoundLevelUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteSoundLevelUpdate.md) &#8596; (void Function(Map&lt;String, double> soundLevels)?)



The remote playing streams audio sound level callback.  
_<span class="feature">read / write</span>_



##### [onRemoteSpeakerStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteSpeakerStateUpdate.md) &#8596; (void Function(String streamID, [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) state)?)



The callback triggered when the state of the remote speaker changes.  
_<span class="feature">read / write</span>_



##### [onRoomExtraInfoUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomExtraInfoUpdate.md) &#8596; (void Function(String roomID, List&lt;[ZegoRoomExtraInfo](../zego_uikit_prebuilt_live_audio_room/ZegoRoomExtraInfo-class.md)> roomExtraInfoList)?)



The callback triggered when there is an update on the extra information of the room.  
_<span class="feature">read / write</span>_



##### [onRoomOnlineUserCountUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomOnlineUserCountUpdate.md) &#8596; (void Function(String roomID, int count)?)



The callback triggered every 30 seconds to report the current number of online users.  
_<span class="feature">read / write</span>_



##### [onRoomStateChanged](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateChanged.md) &#8596; (void Function(String roomID, [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) reason, int errorCode, Map&lt;String, dynamic> extendedData)?)



The callback triggered when the room connection state changes.  
_<span class="feature">read / write</span>_



##### [onRoomStateUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStateUpdate.md) &#8596; (void Function(String roomID, [ZegoRoomState](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md) state, int errorCode, Map&lt;String, dynamic> extendedData)?)



The callback triggered when the room connection state changes.  
_<span class="feature">read / write</span>_



##### [onRoomStreamExtraInfoUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStreamExtraInfoUpdate.md) &#8596; (void Function(String roomID, List&lt;[ZegoStream](../zego_uikit_prebuilt_live_audio_room/ZegoStream-class.md)> streamList)?)



The callback triggered when there is an update on the extra information of the streams published by other users in the same room.  
_<span class="feature">read / write</span>_



##### [onRoomStreamUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomStreamUpdate.md) &#8596; (void Function(String roomID, [ZegoUpdateType](../zego_uikit_prebuilt_live_audio_room/ZegoUpdateType.md) updateType, List&lt;[ZegoStream](../zego_uikit_prebuilt_live_audio_room/ZegoStream-class.md)> streamList, Map&lt;String, dynamic> extendedData)?)



The callback triggered when the number of streams published by the other users in the same room increases or decreases.  
_<span class="feature">read / write</span>_



##### [onRoomTokenWillExpire](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomTokenWillExpire.md) &#8596; (void Function(String roomID, int remainTimeInSecond)?)



Callback notification that room Token authentication is about to expire.  
_<span class="feature">read / write</span>_



##### [onRoomUserUpdate](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomUserUpdate.md) &#8596; (void Function(String roomID, [ZegoUpdateType](../zego_uikit_prebuilt_live_audio_room/ZegoUpdateType.md) updateType, List&lt;[ZegoUser](../zego_uikit_prebuilt_live_audio_room/ZegoUser-class.md)> userList)?)



The callback triggered when the number of other users in the room increases or decreases.  
_<span class="feature">read / write</span>_



##### [onVideoDeviceStateChanged](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onVideoDeviceStateChanged.md) &#8596; (void Function([ZegoUpdateType](../zego_uikit_prebuilt_live_audio_room/ZegoUpdateType.md) updateType, [ZegoDeviceInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md) deviceInfo)?)



The callback triggered when there is a change to video devices (i.e. new device added or existing device deleted).  
_<span class="feature">read / write</span>_





## Static Methods

##### [~~createEngine~~](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md)(int appID, String appSign, bool isTestEnv, [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) scenario, {bool? enablePlatformView}) Future&lt;void>



<code>Deprecated</code> Create ZegoExpressEngine singleton object and initialize SDK. Deprecated since 2.14.0, please use the method with the same name without <code>isTestEnv</code> parameter instead. Please refer to <a href="https://docs.zegocloud.com/article/13315">Testing environment deprecation</a> for more details.  




##### [createEngineWithProfile](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngineWithProfile.md)([ZegoEngineProfile](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile-class.md) profile) Future&lt;void>



Create ZegoExpressEngine singleton object and initialize SDK.  




##### [destroyEngine](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/destroyEngine.md)() Future&lt;void>



Destroy the ZegoExpressEngine singleton object and deinitialize the SDK.  




##### [getVersion](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/getVersion.md)() Future&lt;String>



Gets the SDK's version number.  




##### [isFeatureSupported](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/isFeatureSupported.md)([ZegoFeatureType](../zego_uikit_prebuilt_live_audio_room/ZegoFeatureType.md) featureType) Future&lt;bool>



Query whether the current SDK supports the specified feature.  




##### [setCloudProxyConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setCloudProxyConfig.md)(List&lt;[ZegoProxyInfo](../zego_uikit_prebuilt_live_audio_room/ZegoProxyInfo-class.md)> proxyList, String token, bool enable) Future&lt;void>



Set cloud proxy config.  




##### [setEngineConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setEngineConfig.md)([ZegoEngineConfig](../zego_uikit_prebuilt_live_audio_room/ZegoEngineConfig-class.md) config) Future&lt;void>



Set advanced engine configuration.  




##### [setLocalProxyConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setLocalProxyConfig.md)(List&lt;[ZegoProxyInfo](../zego_uikit_prebuilt_live_audio_room/ZegoProxyInfo-class.md)> proxyList, bool enable) Future&lt;void>



Set local proxy config.  




##### [setLogConfig](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setLogConfig.md)([ZegoLogConfig](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig-class.md) config) Future&lt;void>



Set log configuration.  




##### [setRoomMode](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/setRoomMode.md)([ZegoRoomMode](../zego_uikit_prebuilt_live_audio_room/ZegoRoomMode.md) mode) Future&lt;void>



Set room mode.  












