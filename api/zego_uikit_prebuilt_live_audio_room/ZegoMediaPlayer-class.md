


# ZegoMediaPlayer class













## Constructors

[ZegoMediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/ZegoMediaPlayer.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [clearView](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/clearView.md)() Future&lt;void>



Clears the last frame of the playback control that remains on the control after playback ends.  




##### [enableAccurateSeek](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/enableAccurateSeek.md)(bool enable, [ZegoAccurateSeekConfig](../zego_uikit_prebuilt_live_audio_room/ZegoAccurateSeekConfig-class.md) config) Future&lt;void>



Enable accurate seek and set relevant attributes.  




##### [enableAux](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/enableAux.md)(bool enable) Future&lt;void>



Whether to mix the player's sound into the stream being published.  




##### [enableFrequencySpectrumMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/enableFrequencySpectrumMonitor.md)(bool enable, int millisecond) Future&lt;void>



Whether to enable frequency spectrum monitoring.  




##### [enableRepeat](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/enableRepeat.md)(bool enable) Future&lt;void>



Whether to repeat playback.  




##### [enableSoundLevelMonitor](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/enableSoundLevelMonitor.md)(bool enable, int millisecond) Future&lt;void>



Whether to enable sound level monitoring.  




##### [enableVideoData](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/enableVideoData.md)(bool enable, [ZegoVideoFrameFormat](../zego_uikit_prebuilt_live_audio_room/ZegoVideoFrameFormat.md) format) Future&lt;void>



Whether to video data playback.  




##### [getAudioTrackCount](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getAudioTrackCount.md)() Future&lt;int>



Get the number of audio tracks of the playback file.  




##### [getCurrentProgress](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getCurrentProgress.md)() Future&lt;int>



Get current playing progress.  




##### [getCurrentState](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getCurrentState.md)() Future&lt;[ZegoMediaPlayerState](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerState.md)>



Get the current playback status.  




##### [getIndex](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getIndex.md)() int



Get media player index.  




##### [getNetWorkResourceCache](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getNetWorkResourceCache.md)() Future&lt;[ZegoNetWorkResourceCache](../zego_uikit_prebuilt_live_audio_room/ZegoNetWorkResourceCache-class.md)>



Get the playable duration and size of the cached data of the current network material cache queue  




##### [getPlayVolume](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getPlayVolume.md)() Future&lt;int>



Gets the current local playback volume of the mediaplayer, the range is 0 ~ 200, with the default value of 60.  




##### [getPublishVolume](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getPublishVolume.md)() Future&lt;int>



Gets the current publish volume of the mediaplayer, the range is 0 ~ 200, with the default value of 60.  




##### [getTotalDuration](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/getTotalDuration.md)() Future&lt;int>



Get the total progress of your media resources.  




##### [loadCopyrightedMusicResourceWithPosition](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadCopyrightedMusicResourceWithPosition.md)(String resourceID, int startPosition) Future&lt;[ZegoMediaPlayerLoadResourceResult](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerLoadResourceResult-class.md)>



Load copyrighted music resource.  




##### [loadResource](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResource.md)(String path) Future&lt;[ZegoMediaPlayerLoadResourceResult](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerLoadResourceResult-class.md)>



Load media resource.  




##### [loadResourceFromMediaData](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResourceFromMediaData.md)(Uint8List mediaData, int startPosition) Future&lt;[ZegoMediaPlayerLoadResourceResult](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerLoadResourceResult-class.md)>



Load media resource.  




##### [loadResourceWithPosition](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResourceWithPosition.md)(String path, int startPosition) Future&lt;[ZegoMediaPlayerLoadResourceResult](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerLoadResourceResult-class.md)>



Load media resource.  




##### [muteLocal](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/muteLocal.md)(bool mute) Future&lt;void>



Whether to play locally silently.  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [pause](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/pause.md)() Future&lt;void>



Pause playing.  




##### [resume](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/resume.md)() Future&lt;void>



Resume playing.  




##### [seekTo](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/seekTo.md)(int millisecond) Future&lt;[ZegoMediaPlayerSeekToResult](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerSeekToResult-class.md)>



Set the specified playback progress.  




##### [setActiveAudioChannel](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setActiveAudioChannel.md)([ZegoMediaPlayerAudioChannel](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerAudioChannel.md) audioChannel) Future&lt;void>



Set the playback channel.  




##### [setAudioTrackIndex](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setAudioTrackIndex.md)(int index) Future&lt;void>



Set the audio track of the playback file.  




##### [setAudioTrackMode](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setAudioTrackMode.md)([ZegoMediaPlayerAudioTrackMode](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerAudioTrackMode.md) mode) Future&lt;void>



Set the audio track mode of the player.  




##### [setAudioTrackPublishIndex](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setAudioTrackPublishIndex.md)(int index) Future&lt;void>



Set the audio track for the media file to be publish.  




##### [setNetWorkBufferThreshold](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setNetWorkBufferThreshold.md)(int threshold) Future&lt;void>



Use this interface to set the cache threshold that the media player needs to resume playback. The SDK default value is 5000ms，The valid value is greater than or equal to 1000ms  




##### [setNetWorkResourceMaxCache](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setNetWorkResourceMaxCache.md)(int time, int size) Future&lt;void>



Set the maximum cache duration and cache data size of web materials.  




##### [setPlayerCanvas](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setPlayerCanvas.md)([ZegoCanvas](../zego_uikit_prebuilt_live_audio_room/ZegoCanvas-class.md) canvas) Future&lt;void>



Set the view of the player playing video.
Note: This function is only available in ZegoExpressVideo SDK!  




##### [setPlaySpeed](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setPlaySpeed.md)(double speed) Future&lt;void>



Set the speed of play.  




##### [setPlayVolume](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setPlayVolume.md)(int volume) Future&lt;void>



Set mediaplayer local playback volume.  




##### [setProgressInterval](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setProgressInterval.md)(int millisecond) Future&lt;void>



Set playback progress callback interval.  




##### [setPublishVolume](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setPublishVolume.md)(int volume) Future&lt;void>



Set mediaplayer publish volume.  




##### [setVoiceChangerParam](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setVoiceChangerParam.md)([ZegoMediaPlayerAudioChannel](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerAudioChannel.md) audioChannel, [ZegoVoiceChangerParam](../zego_uikit_prebuilt_live_audio_room/ZegoVoiceChangerParam-class.md) param) Future&lt;void>



Setting up the specific voice changer parameters.  




##### [setVolume](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/setVolume.md)(int volume) Future&lt;void>



Set mediaplayer volume. Both the local play volume and the publish volume are set.  




##### [start](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/start.md)() Future&lt;void>



Start playing.  




##### [stop](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/stop.md)() Future&lt;void>



Stop playing.  




##### [takeSnapshot](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/takeSnapshot.md)() Future&lt;[ZegoMediaPlayerTakeSnapshotResult](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerTakeSnapshotResult-class.md)>



Take a screenshot of the current playing screen of the media player.  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















