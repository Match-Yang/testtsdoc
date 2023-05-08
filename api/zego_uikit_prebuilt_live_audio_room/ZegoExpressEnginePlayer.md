


# ZegoExpressEnginePlayer extension
on [ZegoExpressEngine](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine-class.md)
















## Methods

##### [enableCheckPoc](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/enableCheckPoc.md)(bool enable) Future&lt;void>



Enables or disables frame order detection.  




##### [enableHardwareDecoder](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/enableHardwareDecoder.md)(bool enable) Future&lt;void>



Enables or disables hardware decoding.  




##### [enableVideoSuperResolution](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/enableVideoSuperResolution.md)(String streamID, bool enable) Future&lt;void>



Enable video super resolution.  




##### [isVideoDecoderSupported](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/isVideoDecoderSupported.md)([ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) codecID, {[ZegoVideoCodecBackend](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecBackend.md)? codecBackend}) Future&lt;int>



Whether the specified video decoding format is supported.  




##### [muteAllPlayStreamAudio](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamAudio.md)(bool mute) Future&lt;void>



Can the pull stream receive all audio data.  




##### [muteAllPlayStreamVideo](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/muteAllPlayStreamVideo.md)(bool mute) Future&lt;void>



Can the pull stream receive all video data.  




##### [mutePlayStreamAudio](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamAudio.md)(String streamID, bool mute) Future&lt;void>



Whether the pull stream can receive the specified audio data.  




##### [mutePlayStreamVideo](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/mutePlayStreamVideo.md)(String streamID, bool mute) Future&lt;void>



Whether the pull stream can receive the specified video data.  




##### [setAllPlayStreamVolume](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setAllPlayStreamVolume.md)(int volume) Future&lt;void>



Sets the all stream playback volume.  




##### [setPlayStreamBufferIntervalRange](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayStreamBufferIntervalRange.md)(String streamID, int minBufferInterval, int maxBufferInterval) Future&lt;void>



Set the adaptive adjustment interval range of the buffer for playing stream.  




##### [setPlayStreamCrossAppInfo](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayStreamCrossAppInfo.md)(String streamID, [ZegoCrossAppInfo](../zego_uikit_prebuilt_live_audio_room/ZegoCrossAppInfo-class.md) info) Future&lt;void>



Set up cross App playing stream information.  




##### [setPlayStreamDecryptionKey](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayStreamDecryptionKey.md)(String streamID, String key) Future&lt;void>



Set decryption key for the playing stream.  




##### [setPlayStreamFocusOn](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayStreamFocusOn.md)(String streamID) Future&lt;void>



Set the weight of the pull stream priority.  




##### [setPlayStreamsAlignmentProperty](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayStreamsAlignmentProperty.md)([ZegoStreamAlignmentMode](../zego_uikit_prebuilt_live_audio_room/ZegoStreamAlignmentMode.md) mode) Future&lt;void>



Set the play stream alignment properties.  




##### [setPlayStreamVideoType](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayStreamVideoType.md)(String streamID, [ZegoVideoStreamType](../zego_uikit_prebuilt_live_audio_room/ZegoVideoStreamType.md) streamType) Future&lt;void>



Set play video stream type.  




##### [setPlayVolume](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/setPlayVolume.md)(String streamID, int volume) Future&lt;void>



Sets the stream playback volume.  




##### [startPlayingStream](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/startPlayingStream.md)(String streamID, {[ZegoCanvas](../zego_uikit_prebuilt_live_audio_room/ZegoCanvas-class.md)? canvas, [ZegoPlayerConfig](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig-class.md)? config}) Future&lt;void>



Starts playing a stream from ZEGO RTC server or from third-party CDN. Support multi-room mode.  




##### [stopPlayingStream](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/stopPlayingStream.md)(String streamID) Future&lt;void>



Stops playing a stream.  




##### [takePlayStreamSnapshot](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/takePlayStreamSnapshot.md)(String streamID) Future&lt;[ZegoPlayerTakeSnapshotResult](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerTakeSnapshotResult-class.md)>



Take a snapshot of the playing stream.  


















