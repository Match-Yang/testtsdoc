


# ZegoExpressEngineCustomAudioIO extension
on [ZegoExpressEngine](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine-class.md)
















## Methods

##### [enableAlignedAudioAuxData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableAlignedAudioAuxData.md)(bool enable, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param) Future&lt;void>



Enable feature of throwing audio aux frames which aligned with accompany.  




##### [enableCustomAudioCaptureProcessing](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioCaptureProcessing.md)(bool enable, [ZegoCustomAudioProcessConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig-class.md) config) Future&lt;void>



Enable local collection and custom audio processing(before ear return).  




##### [enableCustomAudioCaptureProcessingAfterHeadphoneMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioCaptureProcessingAfterHeadphoneMonitor.md)(bool enable, [ZegoCustomAudioProcessConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig-class.md) config) Future&lt;void>



Turn on local collection and custom audio processing (after ear return).  




##### [enableCustomAudioIO](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioIO.md)(bool enable, [ZegoCustomAudioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioConfig-class.md) config, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Enables the custom audio I/O function (for the specified channel), support PCM, AAC format data.  




##### [enableCustomAudioPlaybackProcessing](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioPlaybackProcessing.md)(bool enable, [ZegoCustomAudioProcessConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig-class.md) config) Future&lt;void>



Enable custom audio processing for SDK playback audio data.  




##### [enableCustomAudioRemoteProcessing](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/enableCustomAudioRemoteProcessing.md)(bool enable, [ZegoCustomAudioProcessConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig-class.md) config) Future&lt;void>



Enable custom audio processing for remote playing stream.  




##### [fetchCustomAudioRenderPCMData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/fetchCustomAudioRenderPCMData.md)(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param) Future&lt;void>



Fetches PCM audio data of the remote stream from the SDK for custom audio rendering.  




##### [sendCustomAudioCaptureAACData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/sendCustomAudioCaptureAACData.md)(Uint8List data, int dataLength, int configLength, int referenceTimeMillisecond, int samples, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sends AAC audio data produced by custom audio capture to the SDK (for the specified channel).  




##### [sendCustomAudioCapturePCMData](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/sendCustomAudioCapturePCMData.md)(Uint8List data, int dataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, {[ZegoPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel}) Future&lt;void>



Sends PCM audio data produced by custom audio capture to the SDK (for the specified channel).  




##### [startAudioDataObserver](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/startAudioDataObserver.md)(int observerBitMask, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param) Future&lt;void>



Enable audio data observering.  




##### [stopAudioDataObserver](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineCustomAudioIO/stopAudioDataObserver.md)() Future&lt;void>



Disable audio data observering.  


















